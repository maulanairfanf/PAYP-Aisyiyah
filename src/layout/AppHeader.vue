<template>
  <header class="header-global fixed-top">
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
        <li>
          <a slot="title" href="#Home" class="nav-link ml-5" role="button">
            <span class="nav-link-inner--text">Home</span>
          </a>
        </li>
        <li>
          <a slot="title" href="#Kegiatan" class="nav-link ml-5" role="button">
            <span class="nav-link-inner--text">Kegiatan</span>
          </a>
        </li>
        <li class="nav-item dropdown">
          <a
            slot="title"
            class="nav-link  dropdown-toggle ml-5 "
            href="#AboutUs"
            data-toggle="dropdown"
            role="button"
          >
            <span class="nav-link-inner--text">AboutUs</span>
          </a>
          <ul class="dropdown-menu">
            <li>
              <a
                class="dropdown-item nav-link-inner--text font-weight-normal"
                href="#AboutUs"
                >Visi dan Misi</a
              >
            </li>
            <li>
              <a
                class="dropdown-item nav-link-inner--text font-weight-normal"
                href="#AboutUs_SusunanPengurus"
                >Susunan Pengurus</a
              >
            </li>
            <li>
              <a
                class="dropdown-item nav-link-inner--text font-weight-normal"
                href="#AboutUs_TentangPanti"
                >Tentang Panti</a
              >
            </li>
            <li>
              <a
                class="dropdown-item nav-link-inner--text font-weight-normal"
                href="#AboutUs_KriteriaPeneriaan"
                >Kriteria Penerimaan</a
              >
            </li>
          </ul>
        </li>
        <li>
          <a slot="title" href="#Contact" class="nav-link ml-5" role="button">
            <span class="nav-link-inner--text ">Contact</span>
          </a>
        </li>
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

.dropdown-item {
  color: #a1a1a1;
}
.dropdown-item:hover {
  color: #a1a1a1;
}
.dropdown-item:focus {
  color: white;
}
</style>
