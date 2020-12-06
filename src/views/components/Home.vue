<template>
  <section
    class="section section-components m-0 p-0"
  >
    <div>
      <div class="text-center mt-0">
        <img src="img/panti/fotoPanti.png" class="w-100" alt="Foto-Panti" />
      </div>
      <div class="mt-5 d-flex justify-content-around">
        <div class="latar">
          <h3>Latar Belakang</h3>
          <div class="shadow">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione
            eaque vel id. Sit delectus quas sed nostrum alias unde eius
            quibusdam amet necessitatibus beatae! Reprehenderit qui quidem earum
            sit quis? Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            Delectus consequatur commodi unde laborum necessitatibus, quidem
            praesentium debitis accusamus quos ipsa tempora quibusdam optio
            porro, corrupti aperiam voluptates assumenda repellat. Laudantium!
            Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            Reprehenderit earum ipsa similique consectetur! Accusantium vero
            tenetur tempora, saepe suscipit animi cupiditate error quisquam
            voluptatum vel sit nam laudantium cumque nemo!
          </div>
        </div>
      </div>
      <div
        class="container-fluid d-flex row bd-highlight justify-content-around mx-auto"
      >
        <div class="visiMisi mt-5">
          <h3>Visi</h3>
          <div class="shadow">
            <ul>
              <li v-for="(item, i) in items" :key="i">
                {{ item.text }}
              </li>
            </ul>
          </div>
        </div>
        <div class="visiMisi mt-5">
          <h3>Misi</h3>
          <div class="shadow">
            <ul>
              <li v-for="(item, i) in items" :key="i">
                {{ item.text }}
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          text:
            " Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore quia nulla earum quam quae animi quidem sequi mollitia cupiditate nihil quis cumque quod eius, error pariatur. Debitis beatae molestiae accusamus.",
        },
        {
          text:
            " Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore quia nulla earum quam quae animi quidem sequi mollitia cupiditate nihil quis cumque quod eius, error pariatur. Debitis beatae molestiae accusamus.",
        },
        {
          text:
            " Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore quia nulla earum quam quae animi quidem sequi mollitia cupiditate nihil quis cumque quod eius, error pariatur. Debitis beatae molestiae accusamus.",
        },
        {
          text:
            " Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore quia nulla earum quam quae animi quidem sequi mollitia cupiditate nihil quis cumque quod eius, error pariatur. Debitis beatae molestiae accusamus.",
        },
        {
          text:
            " Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore quia nulla earum quam quae animi quidem sequi mollitia cupiditate nihil quis cumque quod eius, error pariatur. Debitis beatae molestiae accusamus.",
        },
      ],
    };
  },
};
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
  width: 700px;
}
</style>
