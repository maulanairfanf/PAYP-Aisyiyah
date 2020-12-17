<template>
  <div>
    <home></home>
    <aboutUs></aboutUs>
    <kegiatan></kegiatan>
    <contact></contact>
  </div>
</template>
<script>
import Home from "./components/Home";
import AboutUs from "./components/AboutUs";
import Kegiatan from "./components/Kegiatan";
import Contact from "./components/Contact";

export default {
  name: "components",
  components: {
    Home,
    AboutUs,
    Kegiatan,
    Contact,
  },
};
</script>
