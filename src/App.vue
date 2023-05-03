<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from "./components/AppHero.vue";

export default{
    name: "App",
    components: {
      AppTitle,
      AppHero,
    }
}

</script>

<template>
  <div class="p-3">
    <AppHero/>

    <h1 class="text-center">Ciao a tutti</h1>

    <AppTitle/>
  </div>
  
</template>

<style scoped>

</style>
