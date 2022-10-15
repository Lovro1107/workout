<template>
  <div class="app-navigation text-white">
    <span class="link home">WORKOUT</span>
    <div class="links">
      <span
          v-for="link in links"
          :key="link"
          class="link text-uppercase"
      >
        {{ link }}
      </span>
    </div>
  </div>
</template>

<script setup lang="ts">
const links = [
  'workouts',
  'programs',
  'healthy living',
  'community',
  'about',
  'store'
]
</script>

<style lang="scss" scoped>
@use '../assets/scss/colors';

.app-navigation {
  display: flex;
  justify-content: space-between;

  .links {
    display: flex;
    gap: 20px;
  }

  .link {
    cursor: pointer;
    font-size: 0.75em;

    &.home {
      font-size: 1em;
      font-weight: 700;
    }
  }
}

</style>
