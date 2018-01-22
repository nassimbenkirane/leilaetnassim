<template>
  <section class="hero is-primary">
    <div class="hero-body has-text-centered">
      <div class="container">
        <router-link tag="h1" class="is-size-2 is-cursive" to="/">
            Leïla & Nassim
        </router-link>
      </div>
    </div>
    <main-navbar/>
  </section>
</template>

<script>
import MainNavbar from '~/components/MainNavbar.vue'

export default {
  data: () => {
    return {

    }
  },
  components: {
    MainNavbar
  },
  mounted () {
    console.log(this.$refs.page)
  }
}
</script>

<style lang="scss">
.hero-body {
  padding: 10px;
}
</style>
