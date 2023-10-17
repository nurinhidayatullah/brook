<template>
    <div class="hero-essential-area swiper-arrow-hover position-relative">
        <swiper
            :speed="1000"
            :navigation="swiperOptions.navigation"
            :effect="'fade'"
            :autoplay="true"
            :loop="true"
        >
            <swiper-slide v-for="slider in sliders" :key="slider.id">
                <div class="hero-essential-slide bg-cover" :style="{backgroundImage: `url(${slider.bgImage})`}">
                    <div class="container">
                        <div class="row">
                            <div class="col-12">
                                <div class="hero-content hero-essential text-white">
                                    <h2 class="hero-title text-white" v-html="slider.heading"></h2>
                                    <h5>{{ slider.subHeading }}</h5>
                                    <!-- <nuxt-link to="/about-us-01" class="btn-essential">Explore Now</nuxt-link> -->
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </swiper-slide>
        </swiper>
        <!-- slider arrow navigation -->
        <div class="ht-swiper-button ht-swiper-button-prev">
            <i class="ion ion-ios-arrow-back"></i>
        </div>
        <div class="ht-swiper-button ht-swiper-button-next">
            <i class="ion ion-ios-arrow-forward"></i>
        </div>
    </div>
</template>

<script>
    import { Swiper, SwiperSlide } from "swiper/vue"
    import SwiperCore, { Navigation, EffectFade, Autoplay } from 'swiper/core'
    SwiperCore.use([Navigation, EffectFade, Autoplay])

    export default {
        components: {
            Swiper,
            SwiperSlide
        },

        data () {
            return {
                swiperOptions: {
                    navigation: {
                        nextEl: '.ht-swiper-button-next',
                        prevEl: '.ht-swiper-button-prev'
                    },
                },
                sliders: [
                    {
                        id: 1,
                        heading: "Susah Cari ART? Lebih Baik Harian - Hemat - Aman - Nyaman",
                        // subHeading: "DITAMBAH KHAWATIR KEAMANANNYA KALO TINGGAL DI RUMAH?",
                        bgImage: "/img/slider/essential-0.png"
                    },
                    {
                        id: 2,
                        heading: "Lelah Menghadapi Drama - Mencari Pengganti Assistent Rumah Tangga?",
                        // subHeading: "DITAMBAH KHAWATIR KEAMANANNYA KALO TINGGAL DI RUMAH?",
                        bgImage: "/img/slider/essential-1.png"
                    },
                    {
                        id: 3,
                        heading: "Kami ART Harian Bikin Harimu Tanpa Bete",
                        // subHeading: "RUMAH SELALU BERSIH DAN RAPI TANPA  KHAWATIR - TANPA NAMBAH KERJAAN !",
                        bgImage: "/img/slider/essential-2.png"
                    },
                    {
                        id: 4,
                        heading: "Rumah Sering Berantakan Karena Aktifitas Bermain?",
                        bgImage: "/img/slider/essential-3.png"
                    },
                    {
                        id: 5,
                        heading: "Apapun situasinya kami hadir untuk keluarga",
                        bgImage: "/img/slider/essential-4.png"
                    },
                    {
                        id: 6,
                        heading: "Dapur Berantakan Butuh Bantuan?",
                        bgImage: "/img/slider/essential-5.png"
                    },
                    {
                        id: 7,
                        heading: "Kami Cekatan Berikan Hasil Rapih dan Kebersihan",
                        bgImage: "/img/slider/essential-6.png"
                    },
                    {
                        id: 8,
                        heading: "Ingin Hidup Lebih Baik dan Bernilai?",
                        bgImage: "/img/slider/essential-7.png"
                    },
                    {
                        id: 9,
                        heading: "Percayakan Kepada Kami - Karena Waktu Keluarga Lebih Berarti",
                        bgImage: "/img/slider/essential-8.png"
                    },
                    {
                        id: 10,
                        heading: "Lelah akan pekerjaan yang tidak diinginkan?",
                        bgImage: "/img/slider/essential-9.png"
                    },
                    {
                        id: 11,
                        heading: "Kami Solusi Berbagai Situasi Rumah Bersih Rapih",
                        bgImage: "/img/slider/essential-10.png"
                    },
                ]
            }
        }
    };
</script>

<style lang="scss" scoped>
    .hero-essential-slide {
        height: 650px;
        display: flex;
        align-items: center;
        position: relative;
        // res
        @media #{$md-layout}{
            height: 600px;
        }
        @media #{$sm-layout}{
            height: 550px;
        }
        @media #{$small-mobile}{
            height: 450px;
        }
        .hero-content {
            max-width: 500px;
            .hero-title {
                font-size: 48px;
                font-weight: 300;
                // res
                @media #{$sm-layout}{
                    font-size: 40px;
                }
                @media #{$small-mobile}{
                    font-size: 32px;
                }
            }
            h5 {
                color: #777;
                font-size: 20px;
                font-weight: 300;
                line-height: 1.2;
                margin-bottom: 40px;
                // res
                @media #{$sm-layout}{
                    color: #444;
                }
                @media #{$small-mobile}{
                    margin-top: 15px;
                    line-height: 1.5;
                }
            }
        }
    }
    .hero-essential-area {
        .ht-swiper-button {
            color: $black;
            font-size: 30px;
            left: 70px;
            width: 68px;
            height: 68px;
            line-height: 68px;
            border-radius: 50%;
            text-align: center;
            background-color: $white;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.01);
            &-next {
                right: 70px;
                left: auto;
            }
        }
    }
</style>