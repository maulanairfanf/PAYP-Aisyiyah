<template>
  <header class="header-global">
    <base-nav
      class="navbar-main d-flex justify-content-start shadow-lg mb-1 bg-white rounded"
      effect="light"
      expand
    >
      <router-link slot="brand" class="mr-5" to="/">
        <img
          src="img/panti/LogoNavbar.png"
          class="img-fluid"
          alt="Logo Panti"
        />
      </router-link>

      <div class="row" slot="content-header" slot-scope="{ closeMenu }">
        <div class="col-6 collapse-brand">
          <h3 class="text-black text-capitalize">PYAP Aisyiyah</h3>
        </div>
        <div class="col-6 collapse-close">
          <close-button @click="closeMenu"></close-button>
        </div>
      </div>

      <ul class="navbar-nav navbar-nav-hover d-flex justify-content-around">
        <!-- <router-link to="/JavascriptComponents/home" class="dropdown-item">Landing</router-link> -->
        <a slot="title" href="#" class="nav-link ml-5" role="button">
          <!-- <i class="ni ni-collection d-lg-none"></i> -->
          <span class="nav-link-inner--text">Home</span>
        </a>
        <a slot="title" href="#" class="nav-link ml-5" role="button">
          <!-- <i class="ni ni-collection d-lg-none"></i> -->
          <span class="nav-link-inner--text">Kegiatan</span>
        </a>
        <a slot="title" href="#" class="nav-link ml-5" role="button">
          <!-- <i class="ni ni-collection d-lg-none "></i> -->
          <span class="nav-link-inner--text">Prestasi</span>
        </a>
        <a slot="title" href="#" class="nav-link ml-5" role="button">
          <!-- <i class="ni ni-collection d-lg-none"></i> -->
          <span class="nav-link-inner--text">About Us</span>
        </a>
        <a slot="title" href="#" class="nav-link ml-5" role="button">
          <!-- <i class="ni ni-collection d-lg-none"></i> -->
          <span class="nav-link-inner--text">Contact</span>
        </a>
      </ul>
    </base-nav>
  </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown,
  },
};
</script>
<style scoped>
.nav-link-inner--text {
  /* font-family: Lato; */
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
}
.nav-link-inner--text:hover {
  color: #4f76a9;
}
</style>
