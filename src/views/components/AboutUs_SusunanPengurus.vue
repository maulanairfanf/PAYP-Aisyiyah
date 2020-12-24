<template>
    <section class="section section-components pb-0" id="AboutUs_SusunanPengurus">
    <div class="container-fluid p-5">
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
              >Kegiatan jalan pagi merupakan olahraga yang dapat dilakukan dimana saja tanpa butuh peralatan khusus apapun. Meskipun sederhana, namun banyak manfaat yang bisa kita dapat dari jalan pagi.</span
            >
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
    
}
</script>

<style scoped>

</style>