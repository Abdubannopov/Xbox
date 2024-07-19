<template>
    <div id="layout-wrapper">
        <!-- Header -->
        <HeaderSide />
        <!-- Header end -->

        <!-- Hero -->
        <div class="hero">
            <Swiper 
                :slides-per-view="1"
                :loop="true"
                :modules="[SwiperNavigation,SwiperAutoplay, SwiperEffectCreative, SwiperPagination]"
                :navigation="{
                      prevEl: '.navigation_prev',
                      nextEl: '.navigation_next',
                }"
                :pagination="{
                    // dynamicBullets: true,
                    el:'.pagination',

                    }">
                    <SwiperSlide class="swiper-nav">
                        <img src="~/assets/images/jpg/starWars.jpg" alt="" width="200">
                    </SwiperSlide>
                    <SwiperSlide class="swiper-nav">
                        <img src="~/assets/images/jpg/starWars.jpg" alt="" width="200">
                    </SwiperSlide>
                    <SwiperSlide class="swiper-nav">
                        <img src="~/assets/images/jpg/starWars.jpg" alt="" width="200">
                    </SwiperSlide>
                    <SwiperSlide class="swiper-nav">
                        <img src="~/assets/images/jpg/starWars.jpg" alt="" width="200">
                    </SwiperSlide>
                    <SwiperSlide class="swiper-nav">
                        <img src="~/assets/images/jpg/starWars.jpg" alt="" width="200">
                    </SwiperSlide>
            </Swiper>
            <div class="pagination"></div>
            <div class="navigation">
            <div class="navigation_prev icon">
                <svg style="transform: rotate(180deg);" xmlns="http://www.w3.org/2000/svg" width="12" height="20" viewBox="0 0 12 20" fill="none">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M10.6621 8.76255C11.3455 9.44597 11.3455 10.554 10.6621 11.2374L3.23744 18.662C2.55402 19.3455 1.44598 19.3455 0.762563 18.662C0.0791456 17.9786 0.0791456 16.8706 0.762563 16.1872L6.94975 9.99999L0.762563 3.8128C0.0791457 3.12939 0.0791456 2.02135 0.762563 1.33793C1.44598 0.654514 2.55402 0.654514 3.23744 1.33793L10.6621 8.76255Z" fill="#8DD83D"/>
                </svg>
            </div>
            <div class="navigation_next icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="12" height="20" viewBox="0 0 12 20" fill="none">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M10.6621 8.76255C11.3455 9.44597 11.3455 10.554 10.6621 11.2374L3.23744 18.662C2.55402 19.3455 1.44598 19.3455 0.762563 18.662C0.0791456 17.9786 0.0791456 16.8706 0.762563 16.1872L6.94975 9.99999L0.762563 3.8128C0.0791457 3.12939 0.0791456 2.02135 0.762563 1.33793C1.44598 0.654514 2.55402 0.654514 3.23744 1.33793L10.6621 8.76255Z" fill="#8DD83D"/>
                </svg>
            </div>
          </div>
        </div>
        <!-- Hero end -->

        <!-- Value -->
        <div class="value hidden">
                <div class="container mx-auto value-inner">
                    <img src="~/assets/images/svg/xbox-light.svg" alt="xbox" class="value-img" width="64" height="64">
                    <h2 class="value-title">The best value</h2>
                    <p class="value-subtitle">in games and entertainment</p>
                    <div class="value-cards gap-y-16">
                        <div class="value-card">
                            <div class="value-card-img-wrapper">
                                <img src="~/assets/images/png/xbox.png" alt="">

                            </div>
                            <div class="value-card-wrapper">
                                <h2 class="value-card-title">XBOX ONE X</h2>
                                <p class="value-card-subtitle">Faster Processing
                                    Smoother Gameplay</p>
                                <a href="#" class="value-card-btn">Explore Consoles & Accessories</a>

                            </div>
                        </div>
                        <div class="value-card">
                            <div class="value-card-img-wrapper">
                                <img src="~/assets/images/png/mixer-logo.png" alt="">

                            </div>
                            <div class="value-card-wrapper">
                                <h2 class="value-card-title">mixer Streaming</h2>
                                <p class="value-card-subtitle">The Next Generation
                                    Of Life Game Streaming</p>
                                <a href="#" class="value-card-btn">Start Watching mixer</a>

                            </div>
                        </div>
                        <div class="value-card">
                            <div class="value-card-img-wrapper">
                                <img src="~/assets/images/png/games.png" alt="">

                            </div>
                            <div class="value-card-wrapper">
                                <h2 class="value-card-title">Free Games Every Month</h2>
                                <p class="value-card-subtitle">Get up to $700 in 
                                free games</p>
                                <a href="#" class="value-card-btn">Get Free Games</a>

                            </div>
                        </div>
                    </div>
                </div>
        </div>
        <!-- Value end -->

        <!-- Xbox design -->
        <div class="design">
            <div class="design-inner container mx-auto">
                <div class="design-wrapper">
                    <h3 class="design-title">Xbox Design Lab</h3>
                    <p class="design-subtitle">Make yours one in a billion with new colors,<br> metallic finishes and rubberized grips.</p>
                    <div class="design-btns">
                        <a href="#" class="design-btns-item design-btns-1">Design Yours</a>
                        <a href="#" class="design-btns-item design-btns-2">Explore Consoles & Accessories</a>
                    </div>
                </div>
            </div>
        </div>
        <!-- Xbox design end -->

        <!-- Footer -->
        <FooterBase/>
        <!-- Footer end -->
    </div>
</template>