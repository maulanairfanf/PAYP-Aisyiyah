<template>
  <footer class="footer background">
    <div class="container-fluid" id="section5">
      <div class="container-fluid" id="section5-1">
        <div class="row text-white">
          <div class="col-md-3">
            <div class="ml-4">
              <img
                src="img/panti/Pantipanti.png"
                class="img-fluid map"
                alt="logo-baru"
              />
              <p class="mt-3">
                Supported by
              </p>

              <img
                src="img/panti/Tel-U.png"
                class="img-fluid map"
                alt="tel-u"
              />
              <br />
              <br />
              <p>@ {{ year }} PAYPA Aisyiyah. All Rights Reserved</p>
            </div>
          </div>
          <div class="col-md-3">
            <div class="d-flex justify-content-md-around ml-4">
              <ul class="navbar-nav">
                <li>
                  <span>Explore</span>
                </li>
                <li>
                  <a class="nav-link text-white" href="#Home">Home</a>
                </li>
                <li>
                  <a class="nav-link text-white" href="#Kegiatan">Kegiatan</a>
                </li>
                <li>
                  <a class="nav-link text-white" href="#AboutUs">About Us</a>
                </li>
                <li>
                  <a class="nav-link text-white" href="#Contact">Contact</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-md-6">
            <ul class="navbar-nav ml-4 mt-xs-2">
              <li>
                <span>Visit</span>
              </li>

              <li>
                <br />
              </li>

              <li>
                <span
                  >Jl.Sam Ratu Langi, No. 34/38. Manahan, Kec. Banjarsari,</span
                ><br />
                <span>Kota Surakarta,Jawa Tengah</span><br />
                <span>57139</span>
              </li>
              <li class="mt-3">
                <span>Contact</span>
              </li>

              <li>
                <br />
              </li>

              <li>
                <span>081329707508 </span><br />
                <span>(Saptono Budi Prasojo, S.Pd, M.Si)</span><br />
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style scoped>
.background {
  background-color: #3c5c8c;
}
</style>
