<template>
  <section class="hero is-primary">
    <div class="hero-body has-text-centered">
      <div class="container">
        <h1 class="is-size-2 is-cursive">
          Leïla & Nassim
        </h1>
      </div>
    </div>
    <main-navbar/>
  </section>
</template>

<script>
import MainNavbar from '~/components/MainNavbar.vue'

export default {
  components: {
    MainNavbar
  }
}
</script>

<style lang="scss">
.hero-body {
  padding: 10px;
}
</style>
