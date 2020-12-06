<template>
  <header class="header-global ">
    <base-nav
      class="navbar-maind-flex justify-content-center shadow-lg mb-1 bg-white rounded"
      effect="light"
      expand
    >
      <router-link slot="brand" class="navbar-brand mr-5" to="/">
        <!-- <h3 class="text-white text-capitalize">PYAP Aisyiyah</h3> -->
        <img src="img/panti/LogoNavbar.png" class="img-fluid  " alt="Logo Panti" />
      </router-link>

      <div class="row" slot="content-header" slot-scope="{ closeMenu }">
        <div class="col-6 collapse-brand">
          <a
            href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
          >
            <h3 class="text-black text-capitalize">PYAP Aisyiyah</h3>
          </a>
        </div>
        <div class="col-6 collapse-close">
          <close-button @click="closeMenu"></close-button>
        </div>
      </div>

      <ul class="navbar-nav navbar-nav-hover align-items-lg-center ml-5">
        <a
          slot="title"
          href="#"
          class="nav-link "
          data-toggle="dropdown"
          role="button"
        >
          <i class="ni ni-collection d-lg-none"></i>
          <span class="nav-link-inner--text">Home</span>
        </a>
        <a
          slot="title"
          href="#"
          class="nav-link"
          data-toggle="dropdown"
          role="button"
        >
          <i class="ni ni-collection d-lg-none"></i>
          <span class="nav-link-inner--text">Kegiatan</span>
        </a>
        <a
          slot="title"
          href="#"
          class="nav-link"
          data-toggle="dropdown"
          role="button"
        >
          <i class="ni ni-collection d-lg-none"></i>
          <span class="nav-link-inner--text">Prestasi</span>
        </a>
        <a
          slot="title"
          href="#"
          class="nav-link"
          data-toggle="dropdown"
          role="button"
        >
          <i class="ni ni-collection d-lg-none"></i>
          <span class="nav-link-inner--text">About Us</span>
        </a>
        <a
          slot="title"
          href="#"
          class="nav-link"
          data-toggle="dropdown"
          role="button"
        >
          <i class="ni ni-collection d-lg-none"></i>
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
<style>
</style>
