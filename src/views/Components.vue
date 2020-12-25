<template>
  <div>
    <home></home>
    <aboutUs></aboutUs>
    <aboutUs_SusunanPengurus></aboutUs_SusunanPengurus>
    <aboutUs_TentangPanti></aboutUs_TentangPanti>
    <kegiatan></kegiatan>
    <contact></contact>
  </div>
</template>
<script>
import Home from "./components/Home";
import AboutUs from "./components/AboutUs";
import AboutUs_SusunanPengurus from "./components/AboutUs_SusunanPengurus";
import AboutUs_TentangPanti from "./components/AboutUs_TentangPanti";
import Kegiatan from "./components/Kegiatan";
import Contact from "./components/Contact";

export default {
  name: "components",
  components: {
    Home,
    AboutUs,
    AboutUs_SusunanPengurus,
    AboutUs_TentangPanti,
    Kegiatan,
    Contact,
  },
};
</script>
