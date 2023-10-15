<template>
  <div class="brook-icon-boxes-area ptb--100">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="brook-section-title text-center mb--45">
            <div class="bkseparator--25"></div>
            <h2 class="heading-40 fw-200">
              <strong
                >PAKET LANGGANAN KEBERSIHAN HEMAT INI COCOK UNTUK :</strong
              >
            </h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-3 col-sm-6" v-for="item in boxList" :key="item.id">
          <div
            class="icon-box text-center no-border bg-transparant vibrate-style"
          >
            <div class="inner">
              <div class="icon">
                <i :class="item.icon"></i>
              </div>
              <div class="content">
                <h5 class="heading heading-h5">{{ item.title }}</h5>
                <!-- <p>{{ item.text }}</p> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      boxList: [
        {
          id: 1,
          icon: "fas fa-home",
          title: "Rumah Tinggal, Bukan Tempat Usaha",
          text:
            "We create an exceptional experience delighting employee and customer",
        },
        {
          id: 2,
          icon: "fa fa-user",
          title: "Penghuni Rumah, Mess, Kost, Asrama, Apartemen",
          text: "We are sincere, reliable and trustworthy about our products",
        },
        {
          id: 3,
          icon: "fas fa-users",
          title: "Rumah Tinggal dengan Maksimal 6 Orang",
          text:
            "We are creative and strive to connect new ideas with business realities",
        },
        {
          id: 4,
          icon: "fa fa-briefcase",
          title: "Buat yang Sibuk dan Mau Nikmatin Hidup Lebih Nyaman, Irit, dan Privasi Terjaga",
          text:
            "We always solve the most important problems to have the biggest impact",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.inner {
    .icon {
        color: red !important;
    }
}</style>
