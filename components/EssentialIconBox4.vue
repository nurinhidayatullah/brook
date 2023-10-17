<template>
    <div class="brook-icon-boxes-area ptb--100">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="brook-section-title text-center mb--45">
              <div class="bkseparator--25"></div>
              <h2 class="heading-40 fw-200">
                <strong
                  >Paket langganan kebersihan hemat ini cocok buat:</strong
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
                  <!-- <p>{{ item.text }}</p> -->
                </div>
              </div>
            </div>
          </div>
        </div>
        <table class="table">
          <thead class="thead-dark" style="background-color: black; !important">
            <tr>
              <th class="w-75">KETERANGAN</th>
              <th class="text-center">HOME STERIL</th>
              <th class="text-center">ART BIASA</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="text-bold">- Biaya (Gaji) Bulanan UMR Jakarta</td>
              <td class="text-right text-bold" style="color: blue">
                Rp1.800.000
              </td>
              <td class="text-right text-bold" style="color: red">
                Rp4.900.000
              </td>
            </tr>
            <tr>
              <td class="text-bold">- Biaya sabun & chemical</td>
              <td class="text-right text-bold" style="color: blue">Rp-</td>
              <td class="text-right text-bold" style="color: red">Rp600.000</td>
            </tr>
          </tbody>
          <thead>
            <tr style="background-color: #2e2e2e; color: whitesmoke">
              <td class="text-bold">TOTAL BIAYA BULANAN</td>
              <td class="text-right text-bold" style="color: blue">
                Rp1.800.000
              </td>
              <td class="text-right text-bold" style="color: red">
                Rp5.500.000
              </td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="text-bold">- Biaya peralatan kebersihan / tahun</td>
              <td class="text-right text-bold" style="color: blue">Rp-</td>
              <td class="text-right text-bold" style="color: red">Rp800.000</td>
            </tr>
            <tr>
              <td class="text-bold">- THR / tahun</td>
              <td class="text-right text-bold" style="color: blue">Rp-</td>
              <td class="text-right text-bold" style="color: red">
                Rp4.900.000
              </td>
            </tr>
          </tbody>
          <thead>
            <tr>
              <td class="text-bold">PERBEDAAN BIAYA TAHUNAN</td>
              <td class="text-right text-bold" style="color: blue">
                Rp21.600.000
              </td>
              <td class="text-right text-bold" style="color: red">
                Rp71.700.000
              </td>
            </tr>
          </thead>
          <thead>
            <tr>
              <td class="text-bold">PENGHEMATAN TAHUNAN</td>
              <td class="text-right text-bold" style="color: blue">Rp-</td>
              <td class="text-right text-bold" style="color: red">
                Rp110.300.000
              </td>
            </tr>
          </thead>
        </table>
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
            icon: "fa fa-check",
            title: "Usaha makan dan minum di tempat, kafe, atau restoran",
            text:
              "Para tukang bersih rumah atau pembersih rumah panggilan kita tuh dilatih buat selalu bersihin rumah sampe bersih banget setiap kali mereka kerja.",
          },
          {
            id: 2,
            icon: "fa fa-check",
            title: "CLOUD KITCHEN",
            text: "Layanan kita nyentuh setiap pojok ruangan, ga cuma bersihin rumah aja tapi juga ngerapihin, bikin rumah kamu jadi rapi, tertata, dan nyaman banget deh",
          },
          {
            id: 3,
            icon: "fa fa-check",
            title: "Kantor yang gak punya cleaning service khusus",
            text:
              "Kita bantu hilangin deh beban kerja jadi housekeeping kamu di rumah, biar kamu bisa fokus sama hidup dan santai bareng keluarga.",
          },
          {
            id: 4,
            icon: "fa fa-check",
            title: " CATERING",
            text:
              "Kita bantu hilangin deh beban kerja jadi housekeeping kamu di rumah, biar kamu bisa fokus sama hidup dan santai bareng keluarga.",
          },
          {
            id: 5,
            icon: "fa fa-check",
            title: "RUMAH YANG DIJADIKAN TEMPAT USAHA",
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
  