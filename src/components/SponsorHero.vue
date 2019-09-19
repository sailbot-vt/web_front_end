<template>
  <section class="hero">
    <b-jumbotron class="hero__jumbotron">
      <template slot="header">Sponsor Us</template>
      <template slot="lead">If you or your company is interested in sponsoring Virginia Tech SailBOT, please let us know. We have lots of real estate on our sail for your logo!</template>

      <b-button class="hero__button" variant="primary" href="mailto:sailbotvt@gmail.com" size="lg">Reach out to us</b-button>
    </b-jumbotron>
  </section>
</template>

<style lang="sass" scoped>
@import "../styles/vars"

.hero
  background-color: rgb(92, 161, 220)

  &__jumbotron
    position: relative
    top: 15%
    bottom: 15%
    max-width: 800px
    margin: 0 auto
    padding: 5%

    text-align: left

    &-hr
      border: none
      height: 1.5px
      color: #212529
      background-color: #212529
</style>
