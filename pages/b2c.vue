<template>
  <div class="main-container">
    <HeroEssential />

    <div class="brook-list-wrapper ptb--150 ptb-md--80 ptb-sm--60">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 col-md-12 col-sm-12 col-12">
            <!-- Start Single List -->
            <div class="bk-list move-up wow">
              <div class="list-header">
                <div class="marker"></div>
                <div class="title-wrap">
                  <h5 class="heading heading-h5">
                    LEBIH FLEKSIBEL DAN KAPAN AJA DIPERLUKAN
                  </h5>
                  <p class="bk_pra">
                    Pilih aja paket per jam yang sesuai jadwal kamu, tanpa ribet
                    kontrak panjang, juga ga perlu mikirin tempat buat
                    <strong>Assistent Rumah Tangga Menginap</strong>. Kami ini
                    <strong>jasa pembersih rumah terdekat</strong>, bisa
                    nyamperin rumah atau apartemen kamu kapan aja dibutuhin.
                  </p>
                </div>
              </div>
            </div>
            <!-- End Single List -->

            <!-- Start Single List -->
            <div class="bk-list mt--45 move-up wow">
              <div class="list-header">
                <div class="marker"></div>
                <div class="title-wrap">
                  <h5 class="heading heading-h5">
                    DIJAMIN BERSIH RAPIH BERGARANSI
                  </h5>
                  <p class="bk_pra">
                    Kami tuh <strong>Jasa Membersihkan Rumah</strong> yang
                    paling pro, hasilnya bersih banget dan buktinya rating dan
                    review-nya paling tinggi di Google. Buat
                    <strong>Jasa cleaning rumah</strong> atau
                    <strong>jasa bersih rumah online</strong>, Kami Ahli
                    Terbukti Testimoni langganan kami
                  </p>
                </div>
              </div>
            </div>
            <!-- End Single List -->
            <!-- Start Single List -->
            <div class="bk-list mt--45 move-up wow">
              <div class="list-header">
                <div class="marker"></div>
                <div class="title-wrap">
                  <h5 class="heading heading-h5">HEMAT BUDGET</h5>
                  <div class="bk-list--2 move-up wow mt-4">
                    <div
                      class="list-header with-ckeck"
                      v-for="list in listsHemat"
                      :key="list.i"
                    >
                      <div class="marker"></div>
                      <div class="title-wrap">
                        <h6 class="heading heading-h5">{{ list.title }}</h6>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!-- End Single List -->
          </div>
          <div class="col-lg-6 col-md-12 col-sm-12 col-12">
            <!-- Start Single List -->
            <div class="bk-list--2 move-up wow">
              <img
                class="img-fluid w-100 my-4"
                src="/img/logo/homesteril.png"
                alt=""
              />
              <div
                class="list-header with-number"
                v-for="list in listsX"
                :key="list.i"
              >
                <div class="marker">
                  <i class="fa fa-times" style="color: red;"></i>
                </div>
                <div class="title-wrap">
                  <h6 class="heading heading-h5">{{ list.title }}</h6>
                </div>
              </div>
            </div>
            <!-- End Single List -->
          </div>
        </div>
      </div>
    </div>

    <EssentialIconBox />
    <div class="case-studis-area pt--120 pt-md--80 pt-sm--60">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="brook-section-title text-center mb--45">
              <div class="bkseparator--25"></div>
              <h2 class="heading-40 fw-200">
                MAU TAU SEBERAPA HEMATNYA PUNYA
                <strong>PEMBANTU HARIAN</strong> DIBANDING DENGAN
                <strong>PEMBANTU RUMAH TANGGA MENGINAP</strong> ?
              </h2>
            </div>
          </div>
        </div>
        <table class="table">
          <thead class="thead-dark">
            <tr>
              <th>
                PERBANDINGAN MEMAKAI JASA KAMI DENGAN MENGGUNAKAN ART BIASA
              </th>
              <th>HOME STERIL</th>
              <th>ART BIASA</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="text-bold">
                <strong>Irit Biaya</strong> Ga Perlu Siapin Tempat Tinggal
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Irit Biaya</strong> Tanpa Biaya Makanan Harian
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Irit Biaya</strong> Ga Perlu Bayar THR
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Irit Biaya</strong> Ga Perlu Bayar Gaji Bulanan Buat yang Jarang Kerja
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Irit Biaya</strong> Ga Perlu Siapin Alat-alat Kayak Vacuum, Pel, Lap, dll
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Kerja Cepat dan Tepat</strong> Efektif Banger
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Petugas Selalu Tersedia</strong> -Ga Pulang Kampung Pas Hari Raya atau Hari Besar*
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
            <tr>
              <td class="text-bold">
                <strong>Jaminan Kerja Aman</strong> Pemilik Rumah Selalu Ada dan Privasi Terjaga karena Kerjaannya Cepet
              </td>
              <td class="text-center">
                <i
                  class="fa fa-check-square text-success"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
              <td class="text-center">
                <i
                  class="fa fa-window-close text-danger"
                  style="font-size: 32px"
                  aria-hidden="true"
                ></i>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <div class="brook-call-to-action bg-danger ptb--40">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-8 col-md-6">
            <div
              class="call-content essential-cta-content text-center text-sm-start"
            >
              <h3 class="text-white wow move-up">
                PESAN SEKARANG DAN RASAKAN KEHIDUPAN LEBIH BERMAKNA!
              </h3>
              <h6 class="text-white wow move-up w-100" style="@media screen and (max-width: 440px) {
                text-align: center;
              }">
                Penawaran Terbatas hanya untuk Hari ini saja
              </h6>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div
              class="call-btn text-center text-md-end mt_mobile--20 wow move-up"
            >
              <nuxt-link
                to="/contact-us-modern"
                class="brook-btn bk-btn-white text-theme btn-sd-size essential-btn"
                >PESAN SEKARANG</nuxt-link
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <PricingItemStyleTwo />
    <EssentialIconBox2 />
    <div
      class="bk-testimonial-area pb--130 pt--80 pb--80 pb_md--80 pb_sm--80 bg_color--6 poss_relative"
    >
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="brook-section-title text-center">
              <h2 class="heading heading-h2">TESTIMONI PELANGGAN KAMI</h2>
            </div>
          </div>
        </div>
        <div class="row mt--85">
          <TestimonialWithoutCarousel />
        </div>
      </div>
    </div>
    <div class="bk-accordion-area ptb--150 ptb-md--80 ptb-sm--60">
      <div class="container">
        <div class="brook-section-title text-center mb--45">
          <div class="bkseparator--25"></div>
          <h2 class="heading-40 fw-200">
            <strong>Yang sering ditanyakan Pelanggan kami (FAQ)</strong>
          </h2>
        </div>
        <AccordionStyleTwo />
      </div>
    </div>
    <div class="brook-call-to-action bg-danger ptb--40">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-8 col-md-6">
            <div
              class="call-content essential-cta-content text-center text-sm-start"
            >
              <h3 class="text-white wow move-up">
                ORDER SEKARANG & GUNAKAN VOUCHER DISK DIBAWAH INI
              </h3>
              <h6 class="text-white wow move-up w-100" style="@media screen and (max-width: 440px) {
                text-align: center;
              }">
                Tunggu Apalagi, Waktunya Hidup Lebih Nyaman 
              </h6>
              <h3 class="text-white wow move-up">
                PENAWARAN BERLAKU SISA {{ msToHours }}: {{ msToMinutes }}:
                {{ msToSeconds }} WIB
              </h3>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div
              class="call-btn text-center text-md-end mt_mobile--20 wow move-up"
            >
              <nuxt-link
                to="/contact-us-modern"
                class="brook-btn bk-btn-white text-theme btn-sd-size essential-btn"
                >PESAN SEKARANG</nuxt-link
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <CarouselWithCaptionOne />
    <PricingItemStyleTwo />
    <BrandLogoCarousel />
    <Footer />
  </div>
</template>

<script>
import CarouselWithCaptionOne from "@/components/sections/CarouselWithCaptionOne";
import TestimonialWithoutCarousel from "@/components/sections/TestimonialWithoutCarousel";
export default {
  components: {
    HeroEssential: () => import("@/components/HeroEssential"),
    EssentialIconBox: () => import("@/components/EssentialIconBox"),
    EssentialIconBox2: () => import("@/components/EssentialIconBox2"),
    PricingItemStyleTwo: () => import("@/components/PricingItemStyleTwo"),
    Footer: () => import("@/components/Footer"),
    BrandLogoCarousel: () => import("@/components/BrandLogoCarousel"),
    AccordionStyleTwo: () => import("@/components/AccordionStyleTwo"),
    TestimonialWithoutCarousel,
    CarouselWithCaptionOne,
  },

  data() {
    return {
      navOpen: false,
      searchOpen: false,
      timer: 43200000,
      listsHemat: [
        {
          title:
            "Bayar cuma buat waktu yang dipake, dengan biaya jasa bersih rumah paling terjangkau karena ga ada biaya makan atau THR. Lebih irit daripada punya <strong>Asistent Rumah Tangga</strong> atau <strong>Pembantu Rumah Tangga</strong> di sana.",
          marker: 1,
        },
        {
          title:
            "Karena udah terbiasa <strong>layanan bersih rumah</strong>, kerjanya cepet dan rapi, jadi <strong>bersih bersih rumahnya</strong>jadi gampang.",
          marker: 2,
        },
        {
          title:
            "Gak usah lagi Ribet Belanja, nambah hemat karena Ga perlu repot beli sabun pembersih khusus buat rumah kamu. Kita yg sediakan semua",
          marker: 3,
        },
      ],
      listsX: [
        {
          title:
            "Nggak Perlu Nyari Asistent Rumah Tangga yang mungkin ga cocok sama keluarga atau kehidupan sehari-hari di rumah",
          marker: 1,
        },
        {
          title:
            "Ga Perlu Repot Cari penyalur pembantu atau yayasan pembantu rumah tangga dengan biaya awal yang mahal",
          marker: 2,
        },
        {
          title:
            "Nggak Perlu cari pembantu tanpa yayasan atau penyalur ART yang ga menjamin keamanan dan kepercayaan di rumah",
          marker: 3,
        },
        {
          title:
            "Privasi rumah terjaga karena ga ada <strong>Penyalur Pembantu atau Yayasan Pembantu Rumah Tangga</strong> yang selalu ada di sekitar aktifitas rumah",
          marker: 4,
        },
        {
          title:
            "<strong>Penyalur ART</strong> atau yg mengaku <strong>Penyalur PRT</strong> terpercaya juga ga bakal bisa kasih garansi ke pemilik rumah soal keamanan pembantu selama bekerja",
          marker: 5,
        },
      ],
    };
  },
  computed: {
    msToHours() {
      var hours = this.timer / (1000 * 60 * 60);
      var absoluteHours = Math.floor(hours);
      var h = absoluteHours > 9 ? absoluteHours : "0" + absoluteHours;
      return h;
    },
    msToMinutes() {
      var hours = this.timer / (1000 * 60 * 60);
      var absoluteHours = Math.floor(hours);
      var minutes = (hours - absoluteHours) * 60;
      var absoluteMinutes = Math.floor(minutes);
      var m = absoluteMinutes > 9 ? absoluteMinutes : "0" + absoluteMinutes;
      return m;
    },
    msToSeconds() {
      var hours = this.timer / (1000 * 60 * 60);
      var absoluteHours = Math.floor(hours);
      var minutes = (hours - absoluteHours) * 60;
      var absoluteMinutes = Math.floor(minutes);
      var seconds = (minutes - absoluteMinutes) * 60;
      var absoluteSeconds = Math.floor(seconds);
      var s = absoluteSeconds > 9 ? absoluteSeconds : "0" + absoluteSeconds;
      return s;
    },
  },
  methods: {
    countdownTimeStart() {
      // Update the count down every 1 second
      let that = this;
      setInterval(function () {
        that.timer = that.timer - 900;
        //that.$store.commit("steril/setTimer2", that.timer);
      }, 1000);
    },
  },
  mounted() {
    this.countdownTimeStart();
    document.body.classList.add(
      "template-color-23",
      "template-font-7",
      "CerebriSans-font"
    );
  },

  unmounted() {
    document.body.classList.remove(
      "template-color-23",
      "template-font-7",
      "CerebriSans-font"
    );
  },

  head() {
    return {
      title: "Home Essential",
    };
  },
};
</script>
