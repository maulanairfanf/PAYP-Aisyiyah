<template>
  <section class="section section-components pb-0" id="section-components">
    <div class="container-fluid kegiatan">
      <div class="mb-5">
        <h3>Kegiatan</h3>
        <span>Our latest activity</span>
      </div>
      <div class="d-flex justify-content-center">
        <div class="shadow d-flex row pb-4 pr-3 pl-3 pt-4 row box kegiatan">
          <div class="col-lg-6 mb-2">
            <img
              src="img/panti/jalanpagi.png"
              alt=""
              class="responsive-img pictKegiatan rounded"
            />
          </div>
          <div class="col-lg-6">
            <h3>Jalan Pagi</h3>
            <span
              >Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Explicabo dolore beatae voluptate quia! Libero pariatur ut quam
              consequatur magnam, alias culpa nostrum possimus doloribus,
              corporis omnis doloremque fugiat dolorem sequi.</span
            >
          </div>
        </div>
      </div>
      <div class="mt-5 justify-content-around d-flex row">
        <div
          class="card rounded mt-3"
          style="width: 22rem"
          v-for="(item, i) in items"
          :key="i"
        >
          <img
            class="w-100 h-100 rounded"
            :src="item.src"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">{{ item.tittle }}</h5>
            <p class="card-text">
              {{ item.text }}
            </p>
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
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/panti/iduladha.png",
        },
      ],
    };
  },
};
</script>

<style scoped>
.kegiatan {
  width: 90%;
}
.shadow {
  box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}
.pictKegiatan {
  width: 100%;
}
</style>