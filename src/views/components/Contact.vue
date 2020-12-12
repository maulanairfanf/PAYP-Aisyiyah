<template>
  <section class="section section-components pb-0 mb-5" id="Contact">
    <div class="container-fluid">
      <div class="text-center">
        <!-- <img src="img/panti/fotoPanti.png" class="img-fluid" alt="Foto-Panti" /> -->
      </div>
      <div class="mb-5 mt-5 d-flex justify-content-around">
        <div class="latar">
          <h3>Contact</h3>
        </div>
      </div>
      <div class="container-fluid d-flex flex-row justify-content-around">
        <div class="visiMisi">
          <div class="shadow row"  >
            <div class="col-lg-3 ">
              <img src="img/panti/maplokasi.png" class="img-fluid w-75 map" alt="Map-Lokasi" />
            </div>
            <div class="col-lg-9 ">
              <img src="img/panti/logoPanti.png" class="img-fluid logo" width = "30%" alt="Logo-Panti" />
              <hr> 
              <p><span class="mr-5">Alamat     : </span>  JL. Sam Ratu Langi, No. 34/38, Manahan, Kec. Banjarsari, Kota Surakarta, Jawa Tengah 57139</p>
              <p><span class="mr-5">No.Telp    : </span>  081329707508 (Saptono Budi Prasojo, S.Pd, M.Si)</p>
              <p><span class="mr-5">Donasi    : </span>  Donatur bisa langsung datang ke Panti Asuhan Yatim Putri Aisyiyah Cabang Kotta Barat Surakarta </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
.latar {
  width: 90%;
}

p{
  font-size: 18px;

}

.shadow {
  box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  padding: 1em; 
}

.map{
  border-radius: 30px ;
}

.visiMisi {
  width: 95%;
  
}
</style>
