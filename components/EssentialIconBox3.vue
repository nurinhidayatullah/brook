<template>
  <div class="brook-icon-boxes-area pt--100">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="brook-section-title text-center mb--45">
            <div class="bkseparator--25"></div>
            <h2 class="heading-60 fw-200">
              <strong
                >Selain itu pengen tahu kenapa harus menjaga kebersihan dapur,
                menjaga kebersihan kamar mandi, menjaga kebersihan lingkungan
                dengan Metode Deep Cleaning. ?<br />
                Nih Kita Kasih tau betapa pentingnya buat reputasi dan juga di
                mata pelanggan usaha kamu</strong
              >
            </h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-sm-6" v-for="item in boxList" :key="item.id">
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
          icon: "fas fa-heart",
          title: "Kesehatan Pelanggan",
          text:
            "Kondisi lingkungan usaha yang kurang bersih bisa menyebabkan penyebaran penyakit dan kontaminasi makanan. Pelanggan yang makan di lingkungan yang kurang bersih berisiko mengalami keracunan makanan atau infeksi yang dapat membahayakan kesehatan mereka. Hal ini bisa berujung pada keluhan pelanggan, pengembalian makanan, atau bahkan tuntutan hukum.",
        },
        {
          id: 2,
          icon: "fa fa-check",
          title: "Reputasi Merk - Kepercayaan terhadap bisnis",
          text:
            "Reputasi dapur umum dan toilet bergantung banget pada seberapa bersihnya. Kalo ada ulasan negatif, pasti bikin hancur bisnis nya , karena itu citranya mesti bagus, biar dapet ulasan positif dan rekomendasi dari pelanggan.",
        },
        {
          id: 3,
          icon: "fas fa-certificate",
          title: "Kepatuhan Regulasi",
          text:
            "Khususnya industri kuliner, banyak negara punya peraturan kesehatan yang ketat. Kalo kebersihan dapur umum atau kamar mandi / toilet umum gak sesuai standar, bisa kena sanksi berat, ditutup sementara atau permanen, atau bahkan dicabut izin usahanya. Jaga kebersihan yang baik itu penting buat memastikan dapur umum dan toilet tetap sesuai regulasi.",
        },
        {
          id: 4,
          icon: "fa fa-user",
          title: "Pengalaman Pelanggan",
          text:
            "Dengan kebersihan terjaga, pengalaman pelanggan jadi lebih positif. Ruangan yang bersih dan rapi memberikan kesan profesional dan perhatian pada detail. Pelanggan merasa nyaman dan senang berada di dapur umum dan toilet yang bersih.",
        },
        {
          id: 5,
          icon: "fa fa-heartbeat",
          title: "Mejaga Makanan Tetap Higienis",
          text:
            "Kebersihan yang baik penting buat keamanan makanan. Jaga dapur dan alat makanan tetap bersih biar makanannya aman untuk dimakan.",
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
