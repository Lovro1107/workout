<template>
  <div class="bg-dark-grey card tutorial">
    <div class="play-icon" />
    <div>
      <span class="tutorial-count">350+</span>
      <span class="text-grey tutorial-text">Video tutorials</span>
    </div>
  </div>
</template>

<style lang="scss">
@use '../assets/scss/colors';

.card.tutorial {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 0.75rem;

  .play-icon {
    width: 2.5rem;
    height: 2.5rem;
    background: colors.$orange;
    border-radius: 50px;
  }

  .tutorial-count {
    display: block;
    font-size: 1.5rem;
    font-weight: 600;
    margin-bottom: 8px;
  }

  .tutorial-text {
    letter-spacing: 0.5px;
    font-weight: 300;
  }
}
</style>
