<template>
  <section class="section section-components" id="AboutUs_KriteriaPeneriaan">
    <div class="m-0">
      <div class="mb-5 ml-5">
        <h1 class="font-weight-bold">Kriteria Penerimaan Anak Asuh</h1>
      </div>
      <div class="m-0 p-0 d-flex row">
        <div class="col-lg-6 ml-lg-5 ">
          <div class="shadow p-3">
            <ol type="a">
              <li
                v-for="(item, i) in Kriteria"
                :key="i"
                class="mt-4 font-weight-bold"
              >
                {{ item.keterangan }}
              </li>
            </ol>
          </div>
        </div>
        <div class="col-lg-5 text-center mt-5">
          <img
            src="img/panti/ilustrasiPenerimaan.svg"
            alt="ilustrasi search"
            class="img-fluid"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      Kriteria: [
        {
          keterangan: "Anak Yatim/Piatu atau Yatim-Piatu atau dhuafa",
        },
        {
          keterangan:
            "Anak minimal usia 7 tahun atau sudah bias mengurus dirinya sendiri",
        },
        {
          keterangan:
            "Pihak keluarga membawa surat permohonan kepada Panti Asuhan",
        },
        {
          keterangan: "Surat Keterangan tidak mampu dari Kalurahan",
        },
        {
          keterangan: "Surat Keterangan kematian bapak/ibu dari Kalurahan",
        },
        {
          keterangan: "Pas foto 3 x 4 (3 lembar)",
        },
        {
          keterangan:
            "Surat Rekomendasi dari pimpinan Aisyiyah Cabang setempat",
        },
        {
          keterangan: "Fotocopy Kartu Keluarga (KK)",
        },
        {
          keterangan: "Fotocopy Akte Kelahiran",
        },
        {
          keterangan: "Fotocopy Kartu Identitas Anak (kalau ada)",
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
