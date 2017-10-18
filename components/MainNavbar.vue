<template>
  <nav class="navbar is-cream" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <button class="button navbar-burger is-transparent is-primary"
        @click="toggleNavbar"
        v-bind:class="{ 'is-active': navbarActive }">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </div>
    <div class="navbar-menu has-text-centered"
      v-bind:class="{ 'is-active': navbarActive }">
      <a class="navbar-item has-text-weight-semibold" href="/">
        Accueil
      </a>
      <a class="navbar-item has-text-weight-semibold" href="/informations">
        Informations
      </a>
      <a class="navbar-item has-text-weight-semibold" href="/rsvp">
        RSVP
      </a>
      <a class="navbar-item has-text-weight-semibold" href="#">
        Liste de mariage
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  data: () => ({
    navbarActive: false
  }),
  methods: {
    toggleNavbar () {
      this.navbarActive = !this.navbarActive
      console.log(this.navbarActive)
    }
  }
}
</script>

<style lang="scss">
.navbar {
  justify-content: center;
  margin: auto;
}
@media (max-width: 1024px) {
  .navbar-brand {
    width: 100vw;
    justify-content: flex-end;
  }
}
.navbar-menu.is-active {
  width: 100vw;
}
</style>
