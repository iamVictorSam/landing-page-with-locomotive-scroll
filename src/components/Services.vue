<template>
  <section id="sticky" data-scroll-section>
    <div class="service-text">
      <h1
        data-scroll
        data-scroll-sticky
        data-scroll-target="#sticky"
        data-scroll-speed="9"
      >
        Services we Offer
      </h1>
    </div>

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

.service-text {
  height: 20px;
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
