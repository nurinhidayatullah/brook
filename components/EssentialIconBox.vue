<template>
  <div class="brook-icon-boxes-area pt--100 pb--40">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="brook-section-title text-center mb--45">
            <div class="bkseparator--25"></div>
            <h2 class="heading-40 fw-200">
              <strong>PAKET PEMBANTU RUMAH TANGGA</strong> HARIAN INI
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
      <table class="table">
        <thead class="thead-dark">
          <tr>
            <th class="w-75">KETERANGAN</th>
            <th>HOME STERIL</th>
            <th>ART BIASA</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="text-bold">Biaya (Gaji) Bulanan</td>
            <td class="text-right text-primary text-bold">Rp550.000</td>
            <td class="text-right text-danger text-bold">Rp2.500.000</td>
          </tr>
          <tr>
            <td class="text-bold">Konsumsi / bulan asumsi'@20.000/hari</td>
            <td class="text-right text-primary text-bold">Rp-</td>
            <td class="text-right text-danger text-bold">Rp600.000</td>
          </tr>
        </tbody>
        <thead class="thead-dark">
          <tr>
            <th class="text-bold">PERBEDAAN BIAYA BULANAN</th>
            <th class="text-right">Rp550.000</th>
            <th class="text-right">Rp3.100.000</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="text-bold">THR / Tahun</td>
            <td class="text-right text-primary text-bold">Rp-</td>
            <td class="text-right text-danger text-bold">Rp2.500.000</td>
          </tr>
          <tr>
            <td class="text-bold">Biaya berobat saat ART sakit / tahun</td>
            <td class="text-right text-primary text-bold">Rp-</td>
            <td class="text-right text-danger text-bold">Rp500.000</td>
          </tr>
        </tbody>
        <thead class="thead-dark">
          <tr>
            <th class="text-bold">PERBEDAAN BIAYA TAHUNAN</th>
            <th class="text-right">Rp6.600.000</th>
            <th class="text-right">Rp40.200.000</th>
          </tr>
        </thead>
        <thead class="thead-dark">
          <tr>
            <th class="text-bold">PENGHEMATAN TAHUNAN</th>
            <th class="text-right"></th>
            <th class="text-right">Rp33.600.000</th>
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
          title:
            "Buat yang Sibuk dan Mau Nikmatin Hidup Lebih Nyaman, Irit, dan Privasi Terjaga",
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
}
</style>
