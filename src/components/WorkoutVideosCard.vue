<template>
  <div class="bg-purple card workout">
    <span class="text-white workout-count">500+</span>
    <span class="text-grey workout-text">Free workout videos</span>
  </div>
</template>

<style lang="scss">
@use '../assets/scss/colors';

.card.workout {
  .workout-count {
    display: block;
    font-size: 2rem;
    font-weight: 600;
    margin-bottom: 8px;
  }

  .workout-text {
    letter-spacing: 0.5px;
    font-weight: 300;
  }
}
</style>
