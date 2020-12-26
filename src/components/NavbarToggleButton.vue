<template>
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    :data-target="target"
    :aria-controls="target"
    :aria-expanded="toggled"
    aria-label="Toggle navigation"
  >
    <span class="navbar-toggler-icon mt-1">
      <i class="fa fa-bars d-lg-none text-dark" style="font-size : 25px"></i>
    </span>
  </button>
</template>
<script>
export default {
  props: {
    target: {
      type: [String, Number],
      description: "Button target element",
    },
    toggled: {
      type: Boolean,
      default: false,
      description: "Whether button is toggled",
    },
  },
};
</script>
<style></style>
