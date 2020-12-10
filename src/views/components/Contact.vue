<template>
  <section class="section section-components pb-0" id="section-components">
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
          <div class="shadow row">
            <div col-lg-6>
              <img src="img/panti/maplokasi.png" class="img-fluid w-75 map" alt="Map-Lokasi" />
            </div>
            <div col-lg-6>
              <img src="img/panti/logoPanti.png" class="img-fluid w-250 logo" alt="Logo-Panti" />
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
  border : 2px solid black
}
</style>
