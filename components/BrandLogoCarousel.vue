<template>
  <div class="bk-brand-area bg_color--1 ptb--60">
    <div class="container">
      <div class="brook-section-title text-center mb--45">
        <div class="bkseparator--25"></div>
        <h4 class="heading-40 fw-200">
          HOME STERIL SERVICE CLIENT
        </h4>
      </div>
      <div class="row">
        <div class="col-lg-12">
          <div class="brand-wrapper">
            <div class="brand__list brand-default brand-style--1">
              <swiper
                :slides-per-view="6"
                :space-between="30"
                :speed="1000"
                :loop="false"
                :autoplay="{ delay: 3000 }"
                :breakpoints="swiperOptions.breakpoints"
              >
                <swiper-slide
                  class="brand"
                  v-for="brand in data"
                  :key="brand.id"
                >
                  <nuxt-link to="/">
                    <img :src="brand.logo" alt="logo image" />
                  </nuxt-link>
                </swiper-slide>
              </swiper>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import data from "../data/brandLogo.json";

import { Swiper, SwiperSlide } from "swiper/vue";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  data() {
    return {
      data,
      swiperOptions: {
        breakpoints: {
          1200: {
            slidesPerView: 5,
          },
          768: {
            slidesPerView: 3,
          },
          480: {
            slidesPerView: 2,
          },
        },
      },
    };
  },
};
</script>
