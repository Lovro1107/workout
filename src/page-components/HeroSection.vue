<template>
  <div class="hero-section">
    <span class="main-title text-white">WORKOUT WITH ME</span>
    <img
        alt="Athlete tying his shoes."
        src="../assets/img/hero.png"
    />

    <p class="subtitle text-grey">
      A huge selection of health and fitness content, healthy recipes and transformation stories to
      help you get fit and stay fit!
    </p>

    <div class="bg-red text-white card join-club">
      Join Club Now!
    </div>

    <div class="bg-dark-grey tutorial card">
      <div class="play-icon" />
      <div>
        <span class="text-white tutorial-count">350+</span>
        <span class="text-grey tutorial-text">Video tutorials</span>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/colors';

.hero-section {
  position: relative;
  margin-top: 180px;
  margin-left: 78px;

  img {
    position: absolute;
    top: 2.5rem;
    left: 44rem;
  }

  .main-title {
    font-family: Agane, 'sans-serif';
    font-size: 10rem;
    letter-spacing: -2px;
    line-height: 11rem;
  }

  .subtitle {
    font-weight: 300;
    width: 650px;
    letter-spacing: 0.5px;
  }

  .join-club {
    margin-top: 48px;
    letter-spacing: 1px;
    font-weight: 600;
  }

  .card.tutorial {
    position: absolute;
    top: 25rem;
    left: 36rem;
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
}
</style>
