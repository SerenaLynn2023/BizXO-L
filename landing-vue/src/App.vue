<!-- <template>
  <div id="app">
    <router-view /> Affiche la page en fonction de l’URL -->

  <!-- </div>
</template> -->
<template>
  <div>
    <HeroSection />
  </div>
</template>

<script>
import HeroSection from './components/HeroSection.vue'

export default {
  components: {
    HeroSection
  }
}
</script>
