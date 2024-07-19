<template>
    <div class="bg-dark">
        <Swiper 
        :slides-per-view="1"
        :loop="true"
        :modules="[SwiperNavigation,SwiperAutoplay, SwiperEffectCreative,SwiperPagination]"
        :navigation="{
              prevEl: '.courses_prev',
              nextEl: '.courses_next',
            }"
        :pagination="{
            // dynamicBullets: true,
            el:'.paginations'
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
        </Swiper>
        <div class="navigation">
            <div class="navigation_prev icon">
              
            </div>
            <div class="navigation_next icon">
              
            </div>
          </div>

    </div>
</template>
<script setup>
</script>
<style>

</style>
