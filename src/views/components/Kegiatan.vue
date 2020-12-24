<template>
  <section class="section section-components pb-0" id="Kegiatan">
    <div class="container-fluid p-5"  >
      <div class="mb-5">
        <h3 class="font-weight-bold">Kegiatan</h3>
        <span>Our latest activity</span>
      </div>
      <div class="d-flex justify-content-center">
        <div class="shadow d-flex row pb-4 pr-3 pl-3 pt-4 row">
          <div class="col-lg-6 mb-2">
            <img
              src="img/panti/jalanpagi.png"
              alt=""
              class="responsive-img pictKegiatan rounded"
            />
          </div>
          <div class="col-lg-6">
            <div class="mt-4 ml-4">
              <h3 class="font-weight-bold">Jalan Pagi</h3>
              
              <span>Kegiatan jalan pagi merupakan olahraga</span>
              <br>
              <span
                > yang dapat dilakukan dimana saja tanpa butuh peralatan khusus apapun. </span
              >
              <br>
              <span>Meskipun sederhana, namun banyak manfaat yang bisa kita dapat dari jalan pagi.</span>
           
            </div>
          </div>
        </div>
      </div>
      <div class="mt-5 justify-content-around d-flex row">
        <div
          class="card rounded mt-3"
          style="width: 24rem"
          v-for="(item, i) in items"
          :key="i"
        >
          <img
            class="rounded w-100"
            
            :src="item.src"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">{{ item.tittle }}</h5>
            
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          tittle: "Jalan Pagi",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/jalanpagicrop.png",
        },
        {
          tittle: "HUT RI",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/hutRI.png",
        },
        {
          tittle: "Shalat Berjamaah",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/solat.png",
        },
        {
          tittle: "Kajian Keputrian",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/kajiankeputrian.png",
        },
        {
          tittle: "Idul Adha",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/iduladha.png",
        },
        {
          tittle: "Rihlah Bersama",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/rihlahbersama.png",
        },
        {
          tittle: "Produksi Telur Asin",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/produksitelurasin.png",
        },
        {
          tittle: "Wirausaha Telur Asin",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/wirausahatelurasin.png",
        },
        
      ],
    };
  },
};
</script>

<style scoped>

.shadow {
  box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  width : 90% !important;
}
.pictKegiatan {
  width: 100%;
}
</style>