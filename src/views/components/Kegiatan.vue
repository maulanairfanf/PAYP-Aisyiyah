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
              src="img/theme/img-2-1200x1000.jpg"
              alt=""
              class="responsive-img pictKegiatan rounded"
            />
          </div>
          <div class="col-lg-6">
            <h3>Nama Kegiatan</h3>
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
          class="card rounded"
          style="width: 22rem"
          v-for="(item, i) in items"
          :key="i"
        >
          <img
            class="card-img-top rounded h-50"
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
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
        },
        {
          tittle: "Title",
          text:
            "Some quick example text to build on the card title and make up the bulk of the card's content.",
          src: "img/theme/img-2-1200x1000.jpg",
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