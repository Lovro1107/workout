<template>
  <div class="hero-section">
    <span class="main-title">WORKOUT WITH ME</span>
    <img
        alt="Athlete tying his shoes."
        src="../assets/img/hero.png"
    />

    <p class="body-text" style="width: 650px;">
      A huge selection of health and fitness content, healthy recipes and transformation stories to
      help you get fit and stay fit!
    </p>

    <div class="bg-red card join-club">
      Join Club Now!
    </div>

    <VideoTutorialCard class="video-tutorial-card" />

    <WorkoutVideosCard class="workout-card" />

    <FeaturedBanner class="featured-banner" />
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

  .join-club {
    margin-top: 48px;
    letter-spacing: 1px;
    font-weight: 600;
  }

  .video-tutorial-card {
    position: absolute;
    top: 25rem;
    left: 36rem;
  }

  .workout-card {
    position: absolute;
    top: 32rem;
    left: 65rem;
  }

  .featured-banner {
    margin-top: 110px;
  }
}
</style>
<script setup lang="ts">
import VideoTutorialCard from "@/components/VideoTutorialCard.vue";
import WorkoutVideosCard from "@/components/WorkoutVideosCard.vue";
import FeaturedBanner from "@/components/FeaturedBanner.vue";
</script>
