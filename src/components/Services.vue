<template>
  <section id="sticky" data-scroll-section>
    <h1 data-scroll data-scroll-sticky data-scroll-target="#sticky">
      Services we Offer
    </h1>

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

#sticky {
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
