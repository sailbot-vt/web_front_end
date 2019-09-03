<template>
  <section class="hero">
    <b-jumbotron class="hero__jumbotron">
      <template slot="header"><img class="hero__image" src="@/assets/logo-color-full.png" alt="Virginia Tech SailBOT" /><hr></template>
      <template slot="lead">We&rsquo;re a Ware Lab design team building 2 meter long autonomous sailboats. In 2019 we placed second in the international SailBOT regatta.</template>
    </b-jumbotron>
  </section>
</template>

<style lang="sass" scoped>
.hero
  background-image: url('../assets/home-hero.jpg')
  background-position: center
  background-repeat: no-repeat
  background-size: cover

  &__image
    width: 200px

  &__jumbotron
    background-color: #e9ecefda

    position: relative
    top: 15%
    bottom: 15%
    max-width: 800px
    margin: 0 auto
    padding: 5%

    text-align: center
</style>
