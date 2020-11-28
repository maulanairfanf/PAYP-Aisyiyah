<template>
  <section class="section section-components pb-0" id="section-components">
    <div class="container-fluid kegiatan">
      <div>
        <h3>Kegiatan</h3>
        <span>Our latest activity</span>
      </div>
      <div class="d-flex justify-content-center">
        <div class="shadow mx-5 d-flex">
          <section>
            <img
              src="img/theme/img-2-1200x1000.jpg"
              alt=""
              class="responsive-img pictKegiatan"
            />
          </section>
          <section>
            <h3>Nama Kegiatan</h3>
            <span
              >Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Explicabo dolore beatae voluptate quia! Libero pariatur ut quam
              consequatur magnam, alias culpa nostrum possimus doloribus,
              corporis omnis doloremque fugiat dolorem sequi.</span
            >
          </section>
        </div>
      </div>
      <div></div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.kegiatan {
  width: 90% !important;
}
.shadow {
  box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  padding: 1em;
}
.pictKegiatan {
  width: 100%;
}
</style>