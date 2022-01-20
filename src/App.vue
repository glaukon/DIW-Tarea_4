<template>
  <logo />
  <migaspan/>
  <centro />
  <pie />
  
  
</template>

<script>
import logo from "./components/logo.vue";
import migaspan from "./components/migaspan.vue"
import centro from "./components/centro.vue";
import pie from "./components/pie.vue";

export default {
  name: "App",
  components: {
    logo,
    migaspan,
    centro,
    pie,
  },
};
</script>

<style>



</style>
