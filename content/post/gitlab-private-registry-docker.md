+++
date = "2016-12-30T11:07:14+01:00"
title = "Un registry Docker privé avec GitLab"
description = "Découvrez la création d'un registry Docker privé, avec GitLab, pour votre site Magento. Rendez-vous sur le site Lumao, Agence Experte Magento"
draft = false
canonical = "https://www.spiriit.com/magento/ressources/gitlab-registry-docker-prive/"
+++
<div class="bg-gray-100 border-l-4 border-primary p-6 my-12 rounded-xl">
  <p class="text-base leading-relaxed mb-4">
    💡 Cet article est désormais disponible dans sa version à jour sur le site Magento de Spiriit.
  </p>
  <a href="https://www.spiriit.com/magento/ressources/gitlab-registry-docker-prive/" class="btn btn-primary mt-2 !text-white">
    À découvrir ici
  </a>
</div>
Aller sur Gitlab.com

Créer un repo privé

Editer le projet :

![GitLab édition du projet](/images/gitlab-private-registry-docker/edition-projet-gitlab.png)

Vérifier que l'option "Container Registry" est activée puis sauvegarder le projet.

Voici la configuration que je recommande :

![GitLab configuration Registry Docker](/images/gitlab-private-registry-docker/parametre-repo-docker.png)

On a donc un repo privé, où on peut mettre notre *Dockerfile* ainsi que notre configuration spécifique, 
un *README* qui explique comment récupèrer un tag spécifique ainsi que notre registry Docker

Vous devriez avoir un nouvel onglet dans le projet : 

![GitLab onglet Registry Docker](/images/gitlab-private-registry-docker/gitlab-onglet-registry.png)

```
docker login registry.gitlab.com
docker build -t registry.gitlab.com/lavoweb/php .
docker push registry.gitlab.com/lavoweb/php
```

A cette étape, on a une ligne dans notre repo :

![GitLab Registry Docker privé premier push](/images/gitlab-private-registry-docker/registry-prive-gitlab-premier-push.png)

```
docker tag registry.gitlab.com/lavoweb/php:latest registry.gitlab.com/lavoweb/php:v5.4.1
docker push registry.gitlab.com/lavoweb/php
```

Maintenant on a également un tag :

![GitLab Registry Docker privé créer un tag](/images/gitlab-private-registry-docker/registry-prive-gitlab-tag.png)

On peut donc pull un tag spécifique

```
docker pull registry.gitlab.com/lavoweb/php:v5.4.1
```

Tous les développeurs d'une équipe auront donc les mêmes paquets installés

Et dans un docker compose :

```
version: '2'
services:
  php:
    image: registry.gitlab.com/lavoweb/php:v5.4.1
```