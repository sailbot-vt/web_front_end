<template>
  <section class="hero">
    <b-jumbotron class="hero__jumbotron">
      <template slot="header">Apply to the team</template>
      <template slot="lead">We have team members from 10 different majors and team members who know nothing at all about sailing, so don&rsquo;t be shy about applying!</template>

      <hr class="hero__jumbotron-hr" />

      <p>Currently live applications:</p>
      <div class="hero__buttons">
        <b-button pill class="hero__button" variant="primary" href="https://forms.gle/yyfARDZimK6hqx3XA" size="lg">Programmer</b-button>
        <b-button pill class="hero__button" variant="warning" href="https://forms.gle/VekHEwATZY2jcadV7" size="lg">Electrical Engineer</b-button>
        <b-button pill class="hero__button" variant="info" href="https://forms.gle/VekHEwATZY2jcadV7" size="lg">Naval Architecture</b-button>
        <b-button pill class="hero__button" variant="info" href="https://forms.gle/hZiawBCXDJMBzin2A" size="lg">Mechanics</b-button>
      </div>

      <p>If you don&rsquo;t see what you want listed here, reach out to <a href="mailto:blasemc1@vt.edu">Blase, our current president</a> and ask if there&rsquo;s a role for you!</p>
    </b-jumbotron>
  </section>
</template>

<style lang="sass" scoped>
@import "../styles/vars"

.hero
  background-color: #212529

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

  &__buttons
    display: flex
    align-items: center
    justify-content: space-around
    max-width: 600px
    margin: 2rem auto

    @include media("<tablet")
      flex-direction: column
      align-items: stretch
      height: 12rem
</style>
