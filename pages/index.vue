<template>
  <section class="section has-text-centered">
    <div class="container">
      <h2 class="title is-size-3 has-text-weight-normal is-cursive">
        Bienvenue sur le site de notre mariage !
      </h2>
      <logo/>
      <h3 class="is-size-6">En cours de création</h3>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  transition: 'page'
}
</script>
