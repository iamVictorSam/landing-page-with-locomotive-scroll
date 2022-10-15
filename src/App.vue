<template>
  <main ref="container">
    <Introduction />
    <Services />
    <Appreciation />
  </main>
</template>

<script>
import Introduction from "./components/Introduction.vue";
import Services from "./components/Services.vue";
import Appreciation from "./components/Appreciation.vue";
import LocomotiveScroll from "locomotive-scroll";

export default {
  components: {
    Introduction,
    Services,
    Appreciation,
  },
  methods: {
    setLocomotiveScroll() {
      new LocomotiveScroll({
        el: this.$refs.container,
        smooth: true,
        multiplier: 2,
      });
    },
  },
  mounted() {
    this.setLocomotiveScroll();
  },
};
</script>
