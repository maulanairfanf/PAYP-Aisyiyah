<template>
  <section class="section section-components m-0 p-0" id="AboutUs">
    <div class="p-0 m-0">
      <div class="text-center mt-0">
        <img src="img/panti/fotoPanti.png" class="w-100" alt="Foto-Panti" />
      </div>
      <div class="mt-5 d-flex justify-content-center">
        <div class="col-xl-6" v-for="(infos, i) in info" :key="i">
          <div class="d-flex justify-content-center">
            <h3 class="mt-3 mb-5 col-xl-6 text-center">
              {{ infos.tittle }}
            </h3>
          </div>
          <div class="mt-3 mb-5 text-center">
            {{ infos.isi }}
          </div>
        </div>
      </div>
      <div class="m-0">
        <img
          src="img/panti/visimisiiilusi.svg"
          class="responsive-img w-100 pos"
          alt="Foto-Panti"
        />
      </div>
      <div class="mt-5">
        <div class="row d-flex justify-content-center">
          <div class="col-xl-2 m-0 p-0">
            <img
              src="img/panti/1.svg"
              class="responsive-img d-none d-xl-block"
              alt="ilustrasi"
            />

            <img
              src="img/panti/3.svg"
              class="responsive-img d-none d-xl-block"
              alt="ilustrasi"
            />
          </div>
          <div class="col-xl-8">
            <div class="col-xl-10">
              <h3 class="font-weight-bold">Visi Kami</h3>
              <ol class="h5">
                <li class="mt-3" v-for="(visi, i) in Visis" :key="i">
                  {{ visi.isi }}
                </li>
              </ol>
              <h3 class="font-weight-bold mt-5">Misi Kami</h3>
              <div class="col-xl-8">
                <ol class="h5">
                  <li class="mt-3">
                    {{ Misis[0].isi }}
                    <ul>
                      <li>{{ Misis[0].rincian[0].rinci }}</li>
                      <li>{{ Misis[0].rincian[1].rinci }}</li>
                      <li>{{ Misis[0].rincian[2].rinci }}</li>
                    </ul>
                  </li>
                  <li class="mt-3">
                    {{ Misis[1].isi }}
                  </li>
                  <li class="mt-3">
                    {{ Misis[2].isi }}
                  </li>
                </ol>
              </div>
            </div>
          </div>
          <div class="col-xl-2 d-flex justify-content-end p-0 m-0">
            <img
              src="img/panti/2.svg "
              class="responsive-img d-none d-xl-block"
              alt="ilustrasi"
            />
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
      info: [
        {
          tittle:
            "PAYPA merupakan panti asuhan yang bertepatan di Kotabarat Surakarta, Jawa Tengah",
          isi:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione eaque vel id. Sit delectus quas sed nostrum alias unde eius quibusdam amet necessitatibus beatae! Reprehenderit qui quidem earum sit quis? Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus consequatur commodi unde laborum necessitatibus, quidem praesentium debitis accusamus quos ipsa tempora quibusdam optio porro, corrupti aperiam voluptates assumenda repellat. Laudantium! Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit earum ipsa similique consectetur! Accusantium vero tenetur tempora, saepe suscipit animi cupiditate error quisquam voluptatum vel sit nam laudantium cumque nemo!",
        },
      ],
      Visis: [
        {
          isi:
            "Berusaha lebih meningkatkan pendidikan, kesehatan, kedisiplinan bagi anak-anak asuh di dalam panti maupun diluar panti",
        },
        {
          isi:
            "Menanamkan rasa disiplin dan tanggung jawab pada anak asuh dalam pembinaan pendidikan sekolah, agama, kebersihan, ketertiban lingkungan dip anti yang langsung dipimpin oleh ketua regu masing-masing anak supaya bisa mandiri dan diawasi oleh bapak ibu pengasuh ",
        },
      ],
      Misis: [
        {
          isi: "Meningkatkan pendidikan anak-anak dalam bidang keagamaan :",
          rincian: [
            {
              rinci:
                "Mengadakan pengajian, pendidikan akhlak, budi pekerti dan ke-Muhammadiyahan",
            },
            {
              rinci: "Memperdalam bacaan Al Qur’an dan diskusi keagamaan ",
            },
            {
              rinci: "Mengadakan/mengikuti penataran-penataran agama ",
            },
          ],
        },
        {
          isi: "	Meningkatkan anak dalam bidang studi",
        },
        {
          isi:
            "Meningkatkan ketrampilan anak untuk mendidik anak asuh supaya mandiri",
        },
      ],
    };
  },
};
</script>
<style scoped>
</style>
