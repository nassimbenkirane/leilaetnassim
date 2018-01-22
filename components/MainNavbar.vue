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
      <router-link to="/" class="navbar-item has-text-weight-semibold">
        Accueil
      </router-link>
      <router-link to="/informations" class="navbar-item has-text-weight-semibold">
        Informations
      </router-link>
      <router-link to="/hebergements" class="navbar-item has-text-weight-semibold">
        Hébergements
      </router-link>
      <router-link to="/rsvp" class="navbar-item has-text-weight-semibold">
        RSVP
      </router-link>
      <router-link to="/liste-de-mariage" class="navbar-item has-text-weight-semibold" >
        Liste de mariage
      </router-link>
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
