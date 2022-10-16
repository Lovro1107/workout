<template>
  <div>
    <span class="text-uppercase text-grey">As featured in</span>
    <div class="logos">
      <img
          v-for="logo in logos"
          :alt="`Logo of ${logo} company`"
          :key="logo"
          :src="`src/assets/img/${logo}-logo.svg`"
      />
    </div>
  </div>
</template>

<script setup lang="ts">
const logos = [
  'nike',
  'buzz-feed',
  'esprit',
  'national-geographic',
  'dw',
  'huffpost'
];
</script>

<style lang="scss">
.logos {
  display: flex;
  gap: 20px;
  margin-top: 32px;
}
</style>
