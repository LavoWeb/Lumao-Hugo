+++
date = "2021-05-10"
title = "Orfeva"
description = ""
draft = false

study = true
custom = true
hero = true
work = true
contact = true
+++

<section class="flex flex-col items-center px-8 mx-auto mt-16 text-center md:container">
    <span class="mb-2 up-title text-primary md:mb-0"> Developpement Web / IOS /Android</span>
    <h2 class="px-10 mb-10 xl-title lg:mb-36">Refonte site e-commerce</h2>
    <div class="relative w-full">
        <span class="absolute hidden w-2/5 mr-0 bg-gray-200 lg:block h-1/2 left-10 -top-14 -z-1 rounded-3xl"></span>
        <div class="flex justify-center overflow-hidden rounded-3xl">
            <img alt="" src="https://via.placeholder.com/1400x800" class="rounded-3xl max-w-none md:max-w-full max-h-400 md:max-h-full" draggable="false"/>
        </div>
    </div>
</section>

<!-- Section 19 -->
<section class="relative flex flex-col items-center px-8 mx-auto mt-16 md:container">
    <div class="container max-w-screen-xl grid-cols-2 gap-24 px-4 lg:grid xl:gap-36 2xl:gap-48">
        <div class="w-full">
            <div class="relative flex flex-col items-start justify-center lg:mt-4 xl:mt-6">
                <h3 class="lg-title"><span class="block text-primary">Le client :</span>Qui est Orfeva ?</h3>
                <span class="divider divider-aside lg:w-16"></span>
            </div>
            <div class="mt-4 mb-5 lg:mb-20">
                <div class="grid self-start grid-cols-1 text-sm leading-normal xl:leading-relaxed lg:text-base">
                    <p class="mb-4 font-bold 2xl:text-lg">Orfeva est artisan de médailles de baptême estampées et dorées à l’or fin. Les modèles proposés sont exclusifs et entièrement fabriqués en France avec les techniques d’antan. Les bijoux sont représentatifs d’un savoir faire traditionnel afin de concevoir un bijou porteur de sens à garder toute sa vie.</p>
                </div>
            </div>
            <div class="mt-4 mb-10">
                <div class="text-sm leading-normal xl:leading-relaxed lg:text-base">
                    <div class="relative text-right 2xl:-left-28 2xl:w-3xl">
                        <img src="https://via.placeholder.com/800x500" class="z-10 rounded-xl lg:rounded-4xl lg:mb-0 2xl:max-w-3xl" alt="" />
                        <a href="" class="relative inline-flex mt-6 text-sm font-bold 2xl:max-w-3xl max-w-max lg:text-lg text-primary group font-accent">
                            <span>En savoir plus</span>
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-4 ml-2">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                            </svg>
                            <span class="w-0 h-0.5 bg-primary absolute -bottom-0.5 group-hover:w-full transition-all"></span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div class="relative w-full mb-10">
            <div class="mt-4 mb-10">
                <img src="https://via.placeholder.com/800x500" class="relative z-10 my-8 rounded-xl lg:rounded-4xl lg:order-last lg:mt-16 lg:mb-0 2xl:mt-16 2xl:max-w-3xl 2xl:-left-28" alt="" />
                <img src="/images/dots.png" class="relative hidden w-48 mt-16 lg:block justify-self-end" alt="" />
            </div>
        </div>
    </div>
    <!-- Bookmark -->
    <div class="absolute right-0 items-center hidden transform rotate-90 bottom-60 3xl:flex">
        <span class="text-xs tracking-widest uppercase">Qui est Orfeva</span>
    </div>
</section>

<section class="relative px-8 py-12 sm:pb-16 bg-gray-theme-100 sm:pt-24">
    <div class="max-w-screen-xl mx-auto">
        <div class="flex flex-col items-center mx-auto text-center">
            <h2 class="xl-title">L'expérience utilisateur</h2>
            <span class="mt-4 divider md:mt-8"></span>
        </div>
        <div class="relative mx-auto my-10 md:my-16">
            <div x-data="{swiper: null}"
                 x-init="swiper = new Swiper($refs.container, {
                loop: true,
                slidesPerView: 1,
                centeredSlides: true,
                slidesPerGroup: 1,
                spaceBetween: 0,
                pagination: {
                    el: '.swiper-pagination',
                    type: 'bullets',
                    bulletClass: 'swiper-pagination-bullet bg-primary',
                },
                })"
                 class="w-full mx-auto mb-5 md:w-3/4 lg:w-full">
                <div class="h-64 overflow-hidden swiper-container rounded-3xl md:h-96 lg:h-700" x-ref="container">
                    <div class="relative h-full cursor-pointer swiper-wrapper rounded-3xl">
                        <div class="relative h-full overflow-hidden swiper-slide">
                            <img alt="" src="https://via.placeholder.com/1200x700" class="absolute object-cover min-w-full min-h-full transform -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" draggable="false"/>
                        </div>
                        <div class="relative h-full overflow-hidden swiper-slide">
                            <img alt="" src="https://via.placeholder.com/1300x600" class="absolute object-cover min-w-full min-h-full transform -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" draggable="false"/>
                        </div>
                        <div class="relative h-full overflow-hidden swiper-slide">
                            <img alt="" src="https://via.placeholder.com/1100x800" class="absolute object-cover min-w-full min-h-full transform -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" draggable="false"/>
                        </div>
                    </div>
                    <div class="absolute top-0 left-0 z-50 w-full h-64 md:h-96 lg:h-700 rounded-3xl shadow-inset-white"></div>
                    <div class="relative mt-10 swiper-pagination"></div>
                </div>
            </div>
            <!-- Bookmark -->
            <div class="absolute items-center hidden transform rotate-90 -right-56 top-1/2 3xl:flex">
                <span class="text-xs tracking-widest uppercase">Une experience unique</span>
            </div>
        </div>
        <div class="flex flex-col items-end mb-16">
            <div class="lg:w-1/2">
                <p class="mb-5 leading-9 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</p>
                <p class="leading-9 text-gray-500"><span class="block font-bold text-black">Réflexion UX</span> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor Aliqua. Ut enim ad minim veniam</p>
            </div>
        </div>
        <div x-data="{swiper: null}"
             x-init="swiper = new Swiper($refs.container, {
                loop: true,
                slidesPerView: 1,
                centeredSlides: true,
                slidesPerGroup: 1,
                spaceBetween: 0,
                pagination: {
                    el: '.swiper-pagination',
                    type: 'bullets',
                    bulletClass: 'swiper-pagination-bullet bg-primary',
                },
                breakpoints: {
                    768: {
                        slidesPerView: 3,
                        spaceBetween: 30,
                        slidesPerGroup: 3,
                    },
                },
                })"
             class="w-3/4 mx-auto mb-5 sm:w-1/2 md:w-full">
            <div class="overflow-hidden swiper-container rounded-3xl" x-ref="container">
                <div class="cursor-pointer swiper-wrapper">
                    <div class="relative mb-8 swiper-slide sm:mb-0">
                        <img alt="" src="https://via.placeholder.com/330x730" class="w-full rounded-3xl" draggable="false"/>
                        <div class="absolute top-0 left-0 w-full h-full rounded-3xl shadow-inset-white"></div>
                    </div>
                    <div class="relative mb-8 swiper-slide sm:mb-0">
                        <img alt="" src="https://via.placeholder.com/330x730" class="w-full rounded-3xl" draggable="false"/>
                        <div class="absolute top-0 left-0 w-full h-full rounded-3xl shadow-inset-white"></div>
                    </div>
                    <div class="relative mb-8 swiper-slide sm:mb-0">
                        <img alt="" src="https://via.placeholder.com/330x730" class="w-full rounded-3xl" draggable="false"/>
                        <div class="absolute top-0 left-0 w-full h-full rounded-3xl shadow-inset-white"></div>
                    </div>
                    <div class="relative mb-8 swiper-slide sm:mb-0">
                        <img alt="" src="https://via.placeholder.com/330x730" class="w-full rounded-3xl" draggable="false"/>
                        <div class="absolute top-0 left-0 w-full h-full rounded-3xl shadow-inset-white"></div>
                    </div>
                </div>
                <div class="relative mt-10 swiper-pagination"></div>
            </div>
        </div>
        <div class="flex justify-center">
            <a href="" class="btn btn-primary-transparent">
                <span>Visitez le site</span>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-4 ml-2 fill-current">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
            </a>
        </div>
    </div>
</section>

<section class="flex flex-col max-w-screen-xl mx-4 mt-5 mb-12 lg:flex-row lg:mt-24 xl:mx-auto">
    <div class="flex flex-col items-center lg:items-end lg:w-1/2">
        <h2 class="text-center lg:text-right lg:pr-16 xl-title">Le challenge et les solutions</h2>
        <span class="relative w-24 my-4 divider lg:right-8"></span>
    </div>
    <div class="mt-5 lg:mt-32 lg:w-1/2">
        <p class="leading-8 text-gray-500 2xl:text-lg">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
</section>

<section class="relative max-w-screen-xl mx-8 mb-10 lg:mb-24 lg:mx-auto md:px-0">
    <img alt="" src="https://via.placeholder.com/1200x700" class="w-full rounded-3xl" draggable="false"/>
    <div class="container relative mx-auto mt-10 lg:px-8 lg:w-7/12 lg:mr-0 lg:ml-auto">
        <ul>
            <li class="relative flex items-baseline pb-4 md:pb-8">
                <div class="leading-8 lg:absolute lg:-left-10">
                    <span class="mr-6 text-lg font-bold text-primary font-accent">01</span>
                </div>
                <div>
                    <p class="font-bold leading-8">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt</p>
                    <p class="leading-8 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, perspiciatis. Nesciunt autem, ad dignissimos fugit at iusto. Asperiores, ad iusto eligendi quia accusantium rerum eveniet explicabo hic obcaecati, doloribus laboriosam.</p>
                </div>
            </li>
            <li class="relative flex items-baseline pb-4 md:pb-8">
                <div class="leading-8 lg:absolute lg:-left-10">
                    <span class="mr-6 text-lg font-bold text-primary font-accent">02</span>
                </div>
                <div>
                    <p class="font-bold leading-8">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt</p>
                    <p class="leading-8 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, perspiciatis. Nesciunt autem, ad dignissimos fugit at iusto. Asperiores, ad iusto eligendi quia accusantium rerum eveniet explicabo hic obcaecati, doloribus laboriosam.</p>
                </div>
            </li>
            <li class="relative flex items-baseline pb-4 md:pb-8">
                <div class="leading-8 lg:absolute lg:-left-10">
                    <span class="mr-6 text-lg font-bold text-primary font-accent">03</span>
                </div>
                <div>
                    <p class="font-bold leading-8">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt</p>
                    <p class="leading-8 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor, perspiciatis. Nesciunt autem, ad dignissimos fugit at iusto. Asperiores, ad iusto eligendi quia accusantium rerum eveniet explicabo hic obcaecati, doloribus laboriosam.</p>
                </div>
            </li>
        </ul>
        <a href="" class="hidden sm:inline-flex text-primary highlighted-label">
            <span>Votre challenge</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-4 ml-2">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
            </svg>
            <span class="w-0 h-0.5 bg-primary absolute -bottom-0.5 group-hover:w-full transition-all"></span>
        </a>
        <!-- Bookmark -->
        <div class="absolute items-center hidden transform rotate-90 -top-40 -right-56 3xl:flex">
            <span class="text-xs tracking-widest uppercase">Challenge et solution</span>
        </div>
    </div>
</section>

<section class="relative flex flex-col py-16 text-white bg-secondary xl:py-32">
    <!-- Section 9 -->
    <div class="flex flex-col px-8 mx-auto lg:flex-row md:container">
        <div class="relative flex flex-col w-full text-sm lg:items-end lg:w-1/2 lg:text-right lg:px-20 lg:text-base lg:h-600">
            <h2 class="mb-2 lg-title">La techno</h2>
            <p class="font-bold lg:text-2xl">Magento, une plateforme puissante</p>
            <span class="relative my-6 bg-white divider lg:-right-12 w-9 lg:w-24 lg:my-10"></span>
            <div class="w-full my-6 transform lg:absolute lg:translate-x-full -right-0 lg:h-full lg:mt-0">
                <span class="absolute left-0 w-1/2 bg-black h-80 lg:h-full rounded-3xl opacity-40"></span>
                <div class="right-0 w-full py-10 lg:absolute lg:w-11/12 h-80 lg:h-full lg:py-24">
                    <div class="relative h-full overflow-hidden bg-white rounded-3xl">
                        <img src="/images/cms/logo-magento-inline.png" class="absolute max-w-full px-10 transform -translate-x-1/2 -translate-y-1/2 max-h-48 top-1/2 left-1/2 lg:px-20" alt="" />
                    </div>
                </div>
            </div>
            <p class="leading-8 opacity-70">Parmi les nombreuses plateformes permettant de développer un site de vente en ligne figure Magento. Cette solution, les experts de Lumao la connaissent bien. En effet, nous travaillons sur et avec Magento depuis ses débuts en 2008. Robuste et complète, soutenue par une communauté dynamique, cette solution est idéale pour tous les types de sites marchands. Pour un volumineux catalogue produits, elle se montre d’ailleurs ultra-performante, en plus de supporter, entre autres, le multilinguisme et le multi-boutiques. Pour la création et le développement de votre boutique Magento, sa maintenance, sa refonte, son optimisation… : faites appel à une agence qui sait exploiter tous les ressorts de ce CMS complet, puissant et évolutif.</p>
        </div>
    </div>
</section>

<section class="py-12 bg-gray-theme-100 sm:py-24">
    <div class="flex flex-col items-center max-w-screen-xl mx-auto text-center">
        <h2 class="max-w-3xl xl-title">La prestation</h2>
        <span class="mt-4 divider md:mt-8"></span>
        <div class="grid-cols-3 gap-4 mx-4 mt-4 sm:grid lg:gap-24 sm:mt-20 sm:mx-0">
            <div class="flex flex-col items-center px-4 py-8 border-b sm:border-0 xl:px-12 sm:rounded-3xl sm:shadow-theme first:shadow-none last:shadow-none">
                <svg xmlns="http://www.w3.org/2000/svg" width="86" height="85" class="fill-current text-primary"><path d="M66.239 8c7.365 0 13.356 5.954 13.356 13.273v41.294c0 7.32-5.99 13.273-13.356 13.273H18.751c-7.365 0-13.356-5.954-13.356-13.273V21.273C5.395 13.953 11.385 8 18.751 8zm10.388 20.647H8.363v33.92c0 5.691 4.661 10.323 10.388 10.323h47.488c5.727 0 10.388-4.632 10.388-10.323v-33.92zm-32.03 12.186c.271-.787 1.15-1.219 1.97-.956l.15.047c.396.124.724.397.91.755.188.36.22.777.087 1.158l-6.26 18.13C41.235 60.6 40.625 61 39.969 61c-.16 0-.324-.024-.486-.076l-.15-.046a1.544 1.544 0 01-.91-.756 1.46 1.46 0 01-.088-1.159zm-11.95 3.483a1.451 1.451 0 011.118-.25c.39.07.737.3.962.633.466.688.383 1.758-.288 2.238l-5.617 4.02 5.617 4.019c.67.48.838 1.425.373 2.113-.227.334-.614.624-1.006.696-.12.023-.246.035-.372.035-.282 0-.563-.064-.787-.224l-7.536-5.392c-.4-.285-.636-.75-.636-1.247 0-.498.237-.962.636-1.249zm18.537-.242c.39-.07.834-.043 1.16.189l7.536 5.392c.398.287.635.751.635 1.25 0 .496-.237.96-.635 1.247l-7.537 5.392a1.469 1.469 0 01-1.117.252 1.485 1.485 0 01-.963-.634l-.085-.125a1.547 1.547 0 01.373-2.114l5.618-4.019-5.618-4.02a1.548 1.548 0 01-.373-2.114c.225-.332.614-.625 1.006-.696zM66.239 10.95H18.751c-5.727 0-10.388 4.632-10.388 10.323v4.424h68.264v-4.424c0-5.691-4.661-10.323-10.388-10.323zm-40.704 4.47c1.169 0 2.12.951 2.12 2.12s-.951 2.12-2.12 2.12-2.12-.951-2.12-2.12.951-2.12 2.12-2.12zm-6.36 0c1.169 0 2.12.951 2.12 2.12s-.951 2.12-2.12 2.12-2.12-.951-2.12-2.12.951-2.12 2.12-2.12zm12.72 0c1.169 0 2.12.951 2.12 2.12s-.951 2.12-2.12 2.12-2.12-.951-2.12-2.12.951-2.12 2.12-2.12zm-6.36 1.413a.709.709 0 00-.707.707c0 .389.318.707.707.707a.709.709 0 00.707-.707.709.709 0 00-.707-.707zm-6.36 0a.709.709 0 00-.707.707c0 .389.318.707.707.707a.709.709 0 00.707-.707.709.709 0 00-.707-.707zm12.72 0a.709.709 0 00-.707.707c0 .389.318.707.707.707a.709.709 0 00.707-.707.709.709 0 00-.707-.707z" fill-rule="evenodd"></path></svg>
                <h3 class="mt-8 mb-3 text-xl font-bold font-accent">Développement</h3>
                <p class="text-sm text-gray-500 sm:text-base">Développement de modules, projets, intégration CSS responsive</p>
                <a class="hidden p-4 mt-10 rounded-full sm:block bg-primary-light" href="">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-4 fill-current text-primary">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                    </svg>
                </a>
            </div>
            <div class="flex flex-col items-center px-4 py-8 bg-white border-b sm:border-0 xl:px-12 sm:rounded-3xl sm:shadow-theme first:shadow-none last:shadow-none">
                <svg xmlns="http://www.w3.org/2000/svg" width="86" height="85" class="fill-current text-primary"><path d="M68.209 7.23c3.305 0 6.023 2.636 6.142 5.904l.004.223v12.18c0 3.294-2.644 6.004-5.922 6.123l-.224.004H45.007v5.438h23.202c3.305 0 6.023 2.636 6.142 5.904l.004.224v12.179c0 3.295-2.644 6.004-5.922 6.123l-.224.004H45.007V75.4h25.968c.845 0 1.536.69 1.536 1.532 0 .796-.616 1.455-1.397 1.526l-.14.006H15.966c-.845 0-1.536-.69-1.536-1.532 0-.796.616-1.455 1.397-1.526l.14-.006h25.967V61.536H18.731c-3.305 0-6.023-2.636-6.142-5.904l-.004-.223v-12.18c0-3.295 2.644-6.004 5.922-6.123l.224-.004h23.202v-5.438H18.731c-3.305 0-6.023-2.636-6.142-5.904l-.004-.224V13.357c0-3.295 2.644-6.004 5.922-6.123l.224-.004h49.478zm0 32.936H18.731a3.08 3.08 0 00-3.068 2.884l-.005.18v12.179a3.078 3.078 0 002.893 3.058l.18.005h49.478a3.08 3.08 0 003.068-2.884l.005-.18V43.23a3.078 3.078 0 00-3.073-3.064zm-41.104 3.217c3.304 0 5.993 2.68 5.993 5.974s-2.689 5.975-5.993 5.975c-3.303 0-5.992-2.68-5.992-5.975 0-3.293 2.689-5.974 5.992-5.974zm0 2.987a2.914 2.914 0 00-2.92 2.91 2.914 2.914 0 002.92 2.911 2.914 2.914 0 002.92-2.91 2.913 2.913 0 00-2.92-2.91zm36.955 1.38c.845 0 1.537.69 1.537 1.532a1.54 1.54 0 01-1.537 1.532H40.09c-.846 0-1.537-.69-1.537-1.532 0-.843.691-1.532 1.537-1.532zm4.149-37.455H18.731a3.08 3.08 0 00-3.068 2.884l-.005.18v12.178a3.078 3.078 0 002.893 3.059l.18.005h49.478a3.08 3.08 0 003.068-2.885l.005-.179v-12.18a3.077 3.077 0 00-3.073-3.063zm-41.104 3.14c3.304 0 5.993 2.68 5.993 5.975 0 3.293-2.689 5.974-5.993 5.974-3.303 0-5.992-2.68-5.992-5.974s2.689-5.975 5.992-5.975zm0 3.064a2.914 2.914 0 00-2.92 2.91 2.914 2.914 0 002.92 2.911 2.914 2.914 0 002.92-2.91 2.914 2.914 0 00-2.92-2.911zm36.955 1.379c.845 0 1.537.689 1.537 1.532a1.54 1.54 0 01-1.397 1.525l-.14.006H40.09a1.538 1.538 0 01-1.537-1.531 1.54 1.54 0 011.397-1.526l.14-.006h23.97z" fill-rule="evenodd"></path></svg>
                <h3 class="mt-8 mb-3 text-xl font-bold font-accent">Hébergement</h3>
                <p class="text-sm text-gray-500 sm:text-base">Hébergement sur nos serveurs cloud haute disponibilité</p>
                <a class="hidden p-4 mt-10 rounded-full sm:block bg-primary-light" href="">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-4 fill-current text-primary">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                    </svg>
                </a>
            </div>
            <div class="flex flex-col items-center px-4 py-8 border-b sm:border-0 xl:px-12 sm:rounded-3xl sm:shadow-theme first:shadow-none last:shadow-none">
                <svg xmlns="http://www.w3.org/2000/svg" width="86" height="85" class="fill-current text-primary"><path d="M74.363 8.074a1.387 1.387 0 011.433.338c.376.375.506.93.338 1.432l-2.061 6.185c-.07.207-.185.395-.339.548L51.756 38.555l21.683 21.683a8.567 8.567 0 012.517 6.097c0 2.31-.895 4.476-2.517 6.1a8.597 8.597 0 01-6.099 2.522 8.596 8.596 0 01-6.098-2.522L39.559 50.752 37.5 52.81a7.187 7.187 0 011.218 4.026c0 1.937-.75 3.752-2.11 5.112L26.316 72.24a10.067 10.067 0 01-7.173 2.96 10.07 10.07 0 01-7.175-2.96c-3.957-3.957-3.957-10.394 0-14.35l10.291-10.292c2.48-2.48 6.328-2.773 9.136-.889l2.061-2.06-5.19-5.19a16.008 16.008 0 01-3.242.337c-4.215 0-8.177-1.64-11.158-4.621a1.484 1.484 0 01-.137-.16A15.692 15.692 0 019.414 21.8a3.771 3.771 0 012.555-3.059 3.779 3.779 0 013.896.916l3.37 3.371a3.395 3.395 0 004.8 0c.636-.637.986-1.49.986-2.398 0-.911-.35-1.763-.987-2.4l-3.371-3.37a3.782 3.782 0 01-.916-3.894 3.782 3.782 0 013.068-2.558c4.96-.707 9.832.92 13.366 4.453l.023.024c3.884 3.9 5.295 9.34 4.25 14.366l5.199 5.2 21.979-21.978c.154-.154.341-.27.547-.339zm-46.991 40.21a4.41 4.41 0 00-3.133 1.295L13.947 59.87c-2.864 2.865-2.864 7.527 0 10.39 2.863 2.864 7.525 2.863 10.39 0l10.291-10.292a4.392 4.392 0 001.29-3.132 4.39 4.39 0 00-1.29-3.133l-4.122-4.124a4.419 4.419 0 00-3.134-1.295zm22.404-7.75l-8.238 8.238 21.684 21.682a5.833 5.833 0 008.237 0 5.783 5.783 0 001.697-4.119c0-1.56-.603-3.022-1.697-4.117L49.776 40.535zM30.472 57.859c.514.513.546 1.41.097 1.97l-.096.107-8.23 8.23c-.263.264-.667.432-1.038.432s-.777-.168-1.04-.431c-.512-.512-.545-1.41-.096-1.97l.097-.108 8.229-8.23c.525-.525 1.553-.525 2.078 0zm35.369 6.977a2.125 2.125 0 012.999 0c.401.4.623.934.623 1.5 0 .57-.222 1.103-.623 1.503-.4.399-.931.62-1.5.62a2.101 2.101 0 01-1.502-.624 2.098 2.098 0 01-.62-1.498c0-.567.221-1.1.623-1.501zm1.5.823a.681.681 0 00-.678.678.678.678 0 10.677-.678zM26.35 53.735c.513.514.545 1.41.096 1.97l-.096.108-8.23 8.23c-.263.262-.667.43-1.04.43-.37 0-.775-.168-1.039-.43-.511-.513-.543-1.41-.096-1.97l.096-.108 8.231-8.23c.546-.547 1.53-.547 2.078 0zm46.243-42.12l-3.216 1.072-22.734 22.735-10.217 10.217-2.95 2.95 1.07 1.072 1.072 1.073L71.52 14.83l1.072-3.216zm-33.085 18.65c-.056.13-.127.254-.186.383-.138.298-.276.596-.434.888-.08.147-.17.287-.255.43-.168.29-.336.58-.525.86-.121.18-.259.352-.387.528-.168.23-.328.46-.51.682a15.88 15.88 0 01-1.03 1.14c-.356.355-.728.693-1.116 1.012a15.666 15.666 0 01-3.793 2.318l4.164 4.164 8.237-8.238zm-5.33-15.445c-2.904-2.89-6.9-4.219-10.97-3.638a.971.971 0 00-.805.672.98.98 0 00.24 1.027l3.37 3.37a6.144 6.144 0 011.808 4.38 6.157 6.157 0 01-1.807 4.38 6.204 6.204 0 01-8.759 0l-3.37-3.373c-.394-.395-.85-.296-1.028-.241a.968.968 0 00-.67.8c-.595 4.168.852 8.297 3.885 11.2l.618.556c.035.033.068.065.1.098 3.457 2.842 8.05 3.617 12.13 2.338.473-.147.931-.319 1.378-.516.075-.032.148-.073.224-.11a13.094 13.094 0 001.428-.781c.278-.175.547-.362.812-.56.122-.09.246-.179.367-.274.37-.298.73-.61 1.072-.952.34-.34.652-.701.95-1.07.099-.123.188-.252.282-.378a13.354 13.354 0 00.808-1.22c.186-.322.358-.653.516-.99.04-.086.086-.168.124-.254.196-.445.37-.903.516-1.373 1.283-4.103.492-8.72-2.387-12.18l-.04-.045z" fill-rule="evenodd"></path></svg>
                <h3 class="mt-8 mb-3 text-xl font-bold font-accent">TMA</h3>
                <p class="text-sm text-gray-500 sm:text-base">Forfait mensualisé
                    de maintenance</p>
                <a class="hidden p-4 mt-10 rounded-full sm:block bg-primary-light" href="">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-4 fill-current text-primary">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                    </svg>
                </a>
            </div>
        </div>
    </div>
</section>

<section class="flex flex-col max-w-screen-xl mx-4 mt-24 mb-12 lg:flex-row md:mb-40 xl:mx-auto">
    <div class="flex flex-col items-center lg:items-end lg:w-1/2">
        <h2 class="text-center lg:pr-16 lg:text-right xl-title">Les chiffres</h2>
        <span class="relative w-24 my-4 divider lg:right-8"></span>
    </div>
    <div class="lg:w-1/2">
        <p class="leading-8 text-gray-500 2xl:text-lg">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt</p>
    </div>
</section>


<section class="relative max-w-screen-xl mx-4 mb-12 lg:mt-32 md:mb-40 xl:mx-auto">
    <div class="lg:mt-44 md:bg-white md:shadow-theme md:rounded-3xl md:pt-10 md:pb-14 font-accent">
        <div class="flex flex-col mx-2 md:flex-row md:justify-around">
            <div class="flex flex-col items-center my-6">
                <div class="flex text-6xl font-bold lg:text-7xl">-50<span class="text-3xl">%</span></div>
                <span class="my-4 divider"></span>
                <div class="text-sm font-bold tracking-wider uppercase">coût d’hebergement</div>
            </div>
            <div class="flex flex-col items-center my-6">
                <div class="flex text-6xl font-bold lg:text-7xl">+12<span class="text-3xl">%</span></div>
                <span class="my-4 divider"></span>
                <div class="text-sm font-bold tracking-wider uppercase">conversion</div>
            </div>
            <div class="relative z-10 flex flex-col items-center py-6 text-white bg-primary md:bg-transparent md:py-0">
                <div class="flex text-6xl font-bold lg:text-7xl">+24<span class="text-3xl">%</span></div>
                <span class="my-4 bg-white divider"></span>
                <div class="text-sm font-bold tracking-wider uppercase">panier moyen</div>
                <div class="box-content absolute hidden w-full h-full px-6 py-12 -mt-20 md:block bg-primary -z-1 rounded-3xl"></div>
            </div>
        </div>
    </div>
    <span class="box-content absolute top-0 hidden w-2/5 h-full py-20 -mt-32 bg-gray-200 md:block rounded-3xl -z-1 right-4 xl:right-8 2xl:right-0 2xl:-mr-28"></span>
    <!-- Bookmark -->
    <div class="absolute items-center hidden transform rotate-90 top-1/2 -right-56 3xl:flex">
        <span class="text-xs tracking-widest uppercase">Les chiffres</span>
    </div>
</section>