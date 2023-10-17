<template>
  <div class="main-container">
    <HeroEssential2 />

    <div class="brook-list-wrapper ptb--150 ptb-md--80 ptb-sm--60">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 col-md-12 col-sm-12 col-12">
            <p class="bk_pra pb--60">
              Masuk akal kan kalo konsumen gak bakal percaya sama reputasi dan
              kebersihan tempat usahamu, kalo dapur umum, kamar mandi, atau
              toilet umumnya aja bikin jijik.<br />
              Kalo kamu Lagi cari solusi buat biar usahamu tetep bersih,
              higienis, dan sesuai standar tinggi. Tenang aja, kami di HOME
              STERIL siap ngebantu banget!
            </p>
            <!-- Start Single List -->
            <div class="bk-list--2 move-up wow">
              <div
                class="list-header with-number"
                v-for="list in listsX"
                :key="list.i"
              >
                <div class="marker">
                  <i class="fa fa-check"></i>
                </div>
                <div class="title-wrap">
                  <h6 class="heading heading-h5">
                    <strong>{{ list.title }}</strong>
                  </h6>
                </div>
              </div>
            </div>
            <!-- End Single List -->
            <p class="bk_pra pt--60">
              <strong>Lalu Apa sih yg dimaksud Jasa Deep Cleaning ?</strong
              ><br />
              Deep cleaning tuh semacam pembersihan total buat semua atau
              beberapa bagian di rumah atau tempat usaha. <br />
              Nah, yang kerjain cuma tim
              <strong>Jasa Cleaning Service</strong> pake peralatan dan bahan
              pembersih khusus yang canggih banget, biar bisa bersihin kotoran
              yang udah numpuk lama dan sulit dihilangin.
            </p>
          </div>
          <div class="col-lg-6 col-md-12 col-sm-12 col-12">
            <!-- Start Single List -->
            <p class="bk_pra pb--20">
              <strong
                >Kenapa harus pilih layanan kebersihan deep cleaning dari home
                steril ?</strong
              >
            </p>
            <div class="bk-list move-up wow">
              <div class="list-header">
                <div class="marker"></div>
                <div class="title-wrap">
                  <h5 class="heading heading-h5">
                    Irit Biaya dan Bisa di Andalkan
                  </h5>
                  <p class="bk_pra">
                    Irit biaya tanpa harus punya cleaning service khusus yang
                    terus ada setiap hari, karena pasti ada biaya tunjangan dan
                    juga biaya peralatan dan cairan khusus yang harus siap sedia
                    setiap saat. Dengan pilihan kami, kamu gak perlu mikirin itu
                    semua.
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
                    Ahli Banget di Bersihin Dapur dan Toilet Umum, juga Bersihin
                    Kamar Mandi
                  </h5>
                  <p class="bk_pra">
                    Kami paham betul gimana pentingnya kebersihan fasilitas
                    umum, terutama di dapur dan toilet, sebagai cerminan
                    higienitas tempat usaha. Tim kita tuh udah dilatih khusus
                    buat nanganin segala tantangan kebersihan yang unik di
                    lingkungan dapur dan toilet.
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
                    Bersih, Cepat, Sehat
                  </h5>
                  <p class="bk_pra">
                    Kebersihan bukan cuma soal penampilan, tapi juga soal
                    kesehatan. Kita paham banget cara ngejaga kebersihan dapur
                    dan kamar mandi pake metode dan produk pembersih yang
                    bener-bener efektif buat bersihin dan ngedisinfect area-area
                    penting. Jadi, kamu bisa yakin kalo dapur dan kamar mandimu
                    bebas dari kuman dan nyaman buat karyawan dan pelanggan yg
                    datang
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
                    Jadwal Kapan Aja di Perlukan
                  </h5>
                  <p class="bk_pra">
                    Kami paham betul kalo setiap dapur umum, toilet, dan cloud
                    kitchen punya jadwal yang padat. Kita siap ngerjain
                    pembersihan pas waktu yang paling nyaman buat kamu, termasuk
                    di luar jam operasional utama.
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
                    Karyawan Bisa Fokus di Operasional
                  </h5>
                  <p class="bk_pra">
                    Kebersihan dapur dan toilet itu benar-benar krusial buat
                    bisnis kamu, biar konsumen merasa nyaman waktu di tempat
                    usahamu. Dengan pakai
                    <strong>jasa bersih toilet, jasa bersih dapur,</strong> dan
                    <strong>jasa deep cleaning</strong> buat usaha kamu,
                    karyawan bisa fokus di operasional yang pastinya udah sibuk
                    banget setiap hari, ga akan maksimal mengerjakan hal penting
                    ini.
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
                    Ahli Pembersihan Khusus
                  </h5>
                  <p class="bk_pra">
                    Tim kita terdiri dari para ahli kebersihan yang udah dilatih
                    dengan baik, mereka paham banget gimana caranya jaga
                    kebersihan lingkungan dan menjaga kesehatan lingkungan
                    usaha. Kita selalu utamain kualitas pelayanan dan kepuasan
                    pelanggan di atas segalanya. Cek aja dan Googling Rating
                    Kami
                  </p>
                </div>
              </div>
            </div>
            <!-- End Single List -->
          </div>
        </div>
      </div>
    </div>

    <EssentialIconBox3 />
    <div class="case-studis-area pt--120 pt-md--80 pt-sm--60">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="brook-section-title text-center mb--45">
              <div class="bkseparator--25"></div>
              <h2 class="heading-30 fw-200">
                Secara keseluruhan,
                <strong>
                  jaga kebersihan dapur dan jaga kebersihan kamar mandi (toilet)
                </strong>
                itu investasi penting buat jaga kesehatan pelanggan, bangun
                reputasi yang baik, patuh regulasi, dan tingkatkan efisiensi
                operasional. Semuanya berkontribusi pada kesuksesan jangka
                panjang bisnis kuliner kamu.
              </h2>
            </div>
          </div>
        </div>
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
                BOOKING SEKARANG
              </h3>
              <h6 class="text-white wow move-up">
                Penawaran Terbatas Hanya untuk Bulan Ini Saja!
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
    <PricingItemStyleTwo2 />
    <div class="container">
      <div class="case-studis-area pt--120 pt-md--80 pt-sm--60">
        <div class="col-lg-12">
          <div class="brook-section-title text-center">
            <h2 class="heading heading-h2">
              Gunakan jasa kami, maka kamu bisa hemat tenaga kerja dan fokus ke
              bisnis.
            </h2>
          </div>
        </div>
        <table class="table">
          <thead class="thead-dark">
            <tr>
              <th>
                PERBANDINGAN MEMAKAI JASA KAMI DENGAN MEMILIKI SDM SENDIRI
              </th>
              <th class="text-center">HOME STERIL</th>
              <th class="text-center">ART BIASA</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="text-bold">
                Standar kebersihan yang tinggi sesuai standar Home Steril
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
                Fokus kepada inti bisnis tanpa terganggu masalah kebersihan
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
              <td class="text-bold">Penghematan waktu dan SDM</td>
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
              <td class="text-bold">Hemat biaya sabun & chemical</td>
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
              <td class="text-bold">Hemat biaya peralatan kebersihan</td>
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
              <td class="text-bold">Hemat Biaya tanpa konsumsi harian</td>
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
                Hemat Biaya Kewajiban Tunjangan Hari Raya
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
    <EssentialIconBox4 />
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
              <h6 class="text-white wow move-up">
                Penawaran Terbatas Hanya untuk Bulan Ini Saja!
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
    HeroEssential2: () => import("@/components/HeroEssential2"),
    EssentialIconBox3: () => import("@/components/EssentialIconBox3"),
    EssentialIconBox4: () => import("@/components/EssentialIconBox4"),
    PricingItemStyleTwo2: () => import("@/components/PricingItemStyleTwo2"),
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
            "Bayar cuma buat waktu yang dipake, dengan biaya jasa bersih rumah paling terjangkau karena ga ada biaya makan atau THR. Lebih irit daripada punya Asistent Rumah Tangga atau pembantu rumah tetap yang tinggal di sana.",
          marker: 1,
        },
        {
          title:
            "Karena udah terbiasa layanan bersih rumah, kerjanya cepet dan rapi, jadi bersihn dan rapihin rumahnya jadi gampang.",
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
          title: "Jasa Bersih Toilet",
          marker: 1,
        },
        {
          title: "Jasa Pembersihan Kloset duduk",
          marker: 2,
        },
        {
          title: "Jasa Pembersihan Kamar Mandi",
          marker: 3,
        },
        {
          title: "Jasa Kebersihan Dapur",
          marker: 4,
        },
        {
          title: "Jasa Kebersihan Lingkungan Usaha",
          marker: 5,
        },
        {
          title: "Jasa Deep Cleaning Rumah",
          marker: 6,
        },
        {
          title: "Jasa Deep Cleaning Tempat Usaha",
          marker: 7,
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
