<template>
  <logo />
  <centro />
  <pie />
  
</template>

<script>
import centro from "./components/centro.vue";
import logo from "./components/logo.vue";
import pie from "./components/pie.vue";

export default {
  name: "App",
  components: {
    logo,
    centro,
    pie,
  },
};
</script>

<style>


</style>
