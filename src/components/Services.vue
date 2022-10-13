<template>
  <section>
    <h1>Services We Offer</h1>

    <div>
      <ServiceText />
      <ServiceText />
      <ServiceText />
    </div>
  </section>
</template>

<style scoped>
section {
  padding: 10rem;
  height: 100vh;
  display: flex;
}

h1 {
  padding-right: 10rem;
}
</style>

<script>
import ServiceText from "./ServiceText.vue";

export default {
  components: {
    ServiceText,
  },
};
</script>
