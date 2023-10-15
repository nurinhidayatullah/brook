<template>
    <div class="brook-icon-boxes-area ptb--100">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="brook-section-title text-center mb--45">
              <div class="bkseparator--25"></div>
              <h2 class="heading-40 fw-200">
                <strong
                  >ADA KELEBIHAN LAINNYA NIH</strong
                >
              </h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-xl-4 col-sm-6" v-for="item in boxList" :key="item.id">
            <div
              class="icon-box text-center no-border bg-transparant vibrate-style"
            >
              <div class="inner">
                <div class="icon">
                  <i :class="item.icon"></i>
                </div>
                <div class="content">
                  <h5 class="heading heading-h5">{{ item.title }}</h5>
                  <p>{{ item.text }}</p>
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
            icon: "fa fa-users",
            title: "Tenaga Kerjanya Keren Abis",
            text:
              "Para tukang bersih rumah atau pembersih rumah panggilan kita tuh dilatih buat selalu bersihin rumah sampe bersih banget setiap kali mereka kerja.",
          },
          {
            id: 2,
            icon: "fa fa-hands",
            title: "Pembersihan mendalam",
            text: "Layanan kita nyentuh setiap pojok ruangan, ga cuma bersihin rumah aja tapi juga ngerapihin, bikin rumah kamu jadi rapi, tertata, dan nyaman banget deh",
          },
          {
            id: 3,
            icon: "fa fa-check",
            title: "Buat Hidup Lebih Oke",
            text:
              "Kita bantu hilangin deh beban kerja jadi housekeeping kamu di rumah, biar kamu bisa fokus sama hidup dan santai bareng keluarga.",
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
  