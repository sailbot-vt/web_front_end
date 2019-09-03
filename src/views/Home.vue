<template>
  <div class="home">
    <HomeHero class="home__hero" />
    <ApplyHero class="home__apply" />
  </div>
</template>

<script>
import HomeHero from '@/components/HomeHero.vue'
import ApplyHero from '@/components/ApplyHero.vue'

export default {
  components: {
    HomeHero,
    ApplyHero
  }
}
</script>

<style lang="sass">
.home
  &__hero
    height: 95vh

  &__apply
    height: 95vh
</style>
