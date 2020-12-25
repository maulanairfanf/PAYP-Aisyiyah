<template>
  <section class="section section-components " id="AboutUs_TentangPanti">
    <div>
      <div class="mb-5 ml-5">
        <h3 class="font-weight-bold">Tentang Panti</h3>
        <span>Sarana & Prasarana</span>
      </div>
      <div class="m-0 p-0">
        <div>
          <img
            src="img/panti/susunanpengurus_Background.svg"
            class="position-absolute"
            alt="Vector"
            width="90%"
          />
          <div class="container-fluid">
            <div class=" shadow col-lg-8 d-flex row ml-4 p-3">
              <div class="col-lg-4">
                <ul>
                  <li class="mt-4" v-for="(item, i) in ListPertama" :key="i">
                    {{ item.Tittle }}
                  </li>
                </ul>
              </div>
              <div class="col-lg-4">
                <ul>
                  <li class="mt-4" v-for="(item, i) in ListKedua" :key="i">
                    {{ item.Tittle }}
                  </li>
                </ul>
              </div>
              <div class="col-lg-4">
                <ul>
                  <li class="mt-4" v-for="(item, i) in ListKetiga" :key="i">
                    {{ item.Tittle }}
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <!-- <div class="col-xl-1 p-0 d-flex align-self-end">
            <img
              src="img/panti/VectorTentangPantiKanan.svg"
              class="d-none d-xl-block d-flex align-self-end"
              alt="Vector"
            />
          </div>

          <div
            class="col-xl-1 d-flex justify-content-end align-self-start - p-0"
          >
            <img
              src="img/panti/VectorTentangPantiKiri.svg"
              class="d-none d-xl-block"
              alt="Vector"
              style="z-index: 1"
            />
          </div> -->
        </div>
      </div>
    </div>
    <div>
      <div class="mb-5 ml-5 mt-5">
        <span>Daftar Anak Panti</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      ListPertama: [
        {
          Tittle: "Halaman Depan",
        },
        {
          Tittle: "Taman",
        },
        {
          Tittle: "Kantor",
        },
        {
          Tittle: "Aula",
        },
        {
          Tittle: "Ruang Pengasuh",
        },
        {
          Tittle: "Dapuar",
        },
      ],
      ListKedua: [
        {
          Tittle: "Kamar A",
        },
        {
          Tittle: "Kamar B",
        },
        {
          Tittle: "Kamar C",
        },
        {
          Tittle: "Kamar D",
        },
        {
          Tittle: "Gudang Depan",
        },
        {
          Tittle: "Gudang Logistik",
        },
      ],
      ListKetiga: [
        {
          Tittle: "Kamar Mandi lt. 1 dan lt. 2",
        },
        {
          Tittle: "Tempat Nyuci",
        },
        {
          Tittle: "Tempat Jemur Pakaian",
        },
        {
          Tittle: "Kamar Pengasuh",
        },
      ],
    };
  },
};
</script>

<style scoped>
.shadow {
  box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.15);
}
</style>
