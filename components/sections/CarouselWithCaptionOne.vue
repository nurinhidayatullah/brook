<template>
    <div class="bk-carousel-slider ptb--150 ptb-md--80 ptb-sm--60 swiper-arrow-hover">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="brook-element-carousel position-relative">
                        <swiper
                            :speed="1000"
                            :loop="true"
                            :space-between="30"
                            :navigation="swiperOptions.navigation"
                            :pagination="swiperOptions.pagination"
                            :breakpoints="swiperOptions.breakpoints"
                        >
                            <!-- Start Single Carousel -->
                            <swiper-slide class="carousle-slider">
                                <div class="thumb">
                                    <img src="/img/carousel/carousel-md-1.jpg" alt="Carousel Image">
                                </div>
                                <div class="content">
                                    <div class="spacing"></div>
                                    <h5>CUCIIN</h5>
                                    <p>Diskon 50%</p>
                                </div>
                            </swiper-slide>
                            <!-- End Single Carousel -->

                            <!-- Start Single Carousel -->
                            <swiper-slide class="carousle-slider">
                                <div class="thumb">
                                    <img src="/img/carousel/carousel-md-2.jpg" alt="Carousel Image">
                                </div>
                                <div class="content">
                                    <div class="spacing"></div>
                                    <h5>CUCIIN</h5>
                                    <p>Diskon 50%</p>
                                </div>
                            </swiper-slide>
                            <!-- End Single Carousel -->

                            <!-- Start Single Carousel -->
                            <swiper-slide class="carousle-slider">
                                <div class="thumb">
                                    <img src="/img/carousel/carousel-md-3.jpg" alt="Carousel Image">
                                </div>
                                <div class="content">
                                    <div class="spacing"></div>
                                    <h5>CUCIIN</h5>
                                    <p>Diskon 50%</p>
                                </div>
                            </swiper-slide>
                            <!-- End Single Carousel -->

                            <!-- Start Single Carousel -->
                            <swiper-slide class="carousle-slider">
                                <div class="thumb">
                                    <img src="/img/carousel/carousel-md-4.jpg" alt="Carousel Image">
                                </div>
                                <div class="content">
                                    <div class="spacing"></div>
                                    <h5>CUCIIN</h5>
                                    <p>Diskon 50%</p>
                                </div>
                            </swiper-slide>
                            <!-- End Single Carousel -->
                        </swiper>

                        <!-- Add Pagination -->
                        <div class="swiper-pagination swiper-dots-bottom"></div>

                        <!-- slider arrow navigation -->
                        <div class="ht-swiper-button ht-swiper-button-prev swiper-arrow-center">
                            <i class="fas fa-angle-left"></i>
                        </div>
                        <div class="ht-swiper-button ht-swiper-button-next swiper-arrow-center">
                            <i class="fas fa-angle-right"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import SwiperCore, { Navigation, Pagination } from 'swiper/core'
    import { Swiper, SwiperSlide } from 'swiper/vue'
    SwiperCore.use([Navigation, Pagination])

    export default {
        components: {
            Swiper,
            SwiperSlide
        },
        data () {
            return {
                swiperOptions: {
                    pagination: {
                        el: '.swiper-pagination',
                        clickable: true,
                    },
                    navigation: {
                        nextEl: '.ht-swiper-button-next',
                        prevEl: '.ht-swiper-button-prev'
                    },
                    // Responsive breakpoints
                    breakpoints: {
                        992:{
                            slidesPerView : 3
                        },

                        768:{
                            slidesPerView : 2
                        },
                        300:{
                            slidesPerView : 1
                        }
                    }
                }
            }
        }
    };
</script>