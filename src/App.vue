<template>
  <Introduction />
  <Services />
  <Appreciation />
</template>

<script>
import Introduction from "./components/Introduction.vue";
import Services from "./components/Services.vue";
import Appreciation from "./components/Appreciation.vue";

export default {
  components: {
    Introduction,
    Services,
    Appreciation,
  },
};
</script>
