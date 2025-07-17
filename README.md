# Status
[![Build Status](https://travis-ci.org/LavoWeb/Lumao-Hugo.svg?branch=master)](https://travis-ci.org/LavoWeb/Lumao-Hugo) 

# Build
```
docker-compose run gulp npm install
docker-compose run gulp gulp css images js
hugo
docker-compose run jekyll jekyll build
```

# Testing
```
hugo server --buildDrafts 
```

# WSL

```
npm install 
hugo server
```

Là on peut check sur localhost nos modifs de contenu.
