<template>
  <logo />
  <centro />
  <pie />
  
  
</template>

<script>
import logo from "./components/logo.vue";
import centro from "./components/centro.vue";
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
