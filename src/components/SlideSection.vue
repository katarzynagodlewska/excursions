<template>
  <swiper
    :spaceBetween="30"
    :centeredSlides="true"
    :autoplay="{
      delay: 2500,
      disableOnInteraction: false,
    }"
    :pagination="{
      clickable: true,
      el: '.pagination',
    }"
    :modules="modules"
  >
    <swiper-slide><SlideItemDiamondBeach /></swiper-slide>
    <swiper-slide><SlideItemGeysir /></swiper-slide>
    <swiper-slide><SlideItem /></swiper-slide>
    <div class="pagination"></div>
  </swiper>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay, Pagination } from "swiper";

import SlideItemDiamondBeach from "./SlideItemDiamondBeach.vue";
import SlideItemGeysir from "./SlideItemGeysir.vue";

import "swiper/css";
import "swiper/css/pagination";
export default {
  name: "SlideSection",
  components: {
    SlideItemDiamondBeach,
    SlideItemGeysir,
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay, Pagination],
    };
  },
};
</script>

<style lang="scss">
@import '../styles/modules/slide.scss';
</style>