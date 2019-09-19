<template>
  <div class="home">
    <HomeHero class="home__hero" />
    <ApplyHero class="home__apply" />
    <SponsorHero class="home__sponsors" />
  </div>
</template>

<script>
import HomeHero from '@/components/HomeHero.vue'
import ApplyHero from '@/components/ApplyHero.vue'
import SponsorHero from '@/components/SponsorHero.vue'

export default {
  components: {
    HomeHero,
    ApplyHero,
    SponsorHero
  }
}
</script>

<style lang="sass">
.home
  &__hero
    height: 95vh

  &__apply
    height: 115vh

  &__sponsors
    height: 75vh
</style>
