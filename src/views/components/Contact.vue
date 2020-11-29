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
          <div class="shadow">
            <ul>
              <img src="img/panti/maplokasi.png" class="img-fluid" alt="Map-Lokasi" />
              <img src="img/panti/logoPanti.png" class="img-fluid" alt="Logo-Panti" />
            </ul>

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

.visiMisi {
  width: 95%;
  border : 2px solid black
}
</style>
