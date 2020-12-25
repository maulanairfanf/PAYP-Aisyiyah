<template>
  <section class="section section-components " id="AboutUs_TentangPanti">
    <div>
      <div class="mb-5 ml-5 font-weight-bold">
        <div class=" p-0 d-flex justify-content-end">
          <img
            src="img/panti/VectorTentangPantiKanan.svg"
            class="position-absolute responsive-img d-none d-xl-block"
            alt="Vector"
          />
        </div>
        <h3>Tentang Panti</h3>
        <span>Sarana & Prasarana</span>
      </div>
      <div class="d-flex">
        <img
          src="img/panti/susunanpengurus_Background.svg"
          class="position-absolute d-none d-xl-block d-flex"
          alt="Vector"
          width="90%"
        />

        <div class=" shadow col-lg-7 d-flex ml-lg-5  p-3 row m-0">
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
    </div>
    <div class="mt-5">
      <div class="mb-5 ml-5 mt-5">
        <span class="font-weight-bold">Daftar Anak Panti</span>
      </div>
      <div
        class="shadow d-flex justify-content-around col-lg-11 ml-lg-5  p-lg-5 mt-5"
      >
        <div class="col-lg-10">
          <div class="table-responsive rounded">
            <table
              class="table table-bordered"
              style="border: 2px solid #D3D3D3"
            >
              <thead>
                <tr class="bg-secondary">
                  <th scope="col">Nama</th>
                  <th scope="col">Tempat/Tamggal Lahir</th>
                  <th scope="col">Pendidikan</th>
                </tr>
              </thead>
              <tbody>
                <tr v-for="(people, i) in AnakPanti" :key="i">
                  <td>{{ people.nama }}</td>
                  <td>{{ people.ttl }}</td>
                  <td>{{ people.pendidikan }}</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
      <!-- <div class="d-flex justify-content-start align-self-start  p-0">
        <img
          src="img/panti/VectorTentangPantiKiri.svg"
          class="position-absolute responsive-img d-none d-xl-block"
          alt="Vector"
        />
      </div> -->
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      AnakPanti: [
        {
          nama: "Dela Nur Aisyah",
          ttl: "Semarang , 1 maret 1999",
          pendidikan: "Mahasiswa",
        },
        {
          nama: "Jinny Permata Sanny",
          ttl: "Surakarta, 15 Januari 1998",
          pendidikan: "Mahasiswa",
        },
        {
          nama: "Evi Sunarti",
          ttl: " Kr. Pendeta, 19 Februari 1997",
          pendidikan: "Mahasiswa",
        },
        {
          nama: "Dinda Novita Sari",
          ttl: " Surakarta, 7 Oktober 1999",
          pendidikan: "Mahasiswa",
        },
        {
          nama: "Anggun Nilam Sari",
          ttl: " Brebes, 16 Agustus 2000",
          pendidikan: "Mahasiswa",
        },
        {
          nama: "Mia Linda Wati",
          ttl: "	Klaten, 25 Mei 2001",
          pendidikan: "Mahasiswa",
        },
        {
          nama: "Mutmainah Wulan Agustina",
          ttl: " Boyolali, 17 Agustus 2003",
          pendidikan: " MAN II/kelas XI",
        },
        {
          nama: "Putri Reona Wardani",
          ttl: "  Surakarta, 30 Maret 2004",
          pendidikan: " MAN II/kelas XI",
        },
        {
          nama: "Titis Arlinda Ristanti",
          ttl: "Sragen, 26 Mei 2003",
          pendidikan: " MAN II/kelas XI",
        },
        {
          nama: "Choirul Asyifa",
          ttl: "Boyolali, 21 September 2005",
          pendidikan: "SMK IV Muhammadiyah/kelas X",
        },
        {
          nama: "Aulia Afriana",
          ttl: " Surakarta, 14 April 2013",
          pendidikan: "SD Muhammadiyah 20/kelas I",
        },
      ],
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
