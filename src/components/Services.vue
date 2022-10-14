<template>
  <section>
    <h1>Services we Offer</h1>

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
  display: flex;
  background-color: #f4fdff;
}

h1 {
  padding-right: 10rem;
  font-size: 3rem;
  color: blue;
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
