<template>
  <div class="app-container">
    <AppNavigation />

    <HeroSection/>
  </div>
</template>

<script setup lang="ts">
import AppNavigation from "@/page-components/AppNavigation.vue";
import HeroSection from "@/page-components/HeroSection.vue";
</script>

<style lang="scss">
.app-container {
  max-width: 1280px;
  margin: auto;
  padding: 48px 64px;
}

</style>
