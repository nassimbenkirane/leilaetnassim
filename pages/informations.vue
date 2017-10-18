<template>
  <section class="section has-text-centered">
    <div class="container is-size-5">
      <h1 class="is-size-3 is-cursive">
        Ici, vous trouverez toutes les informations
      </h1>

      <section class="section">
        <h2 class="title is-size-4">Cérémonie de mariage à Paris</h2>

        <p>Nous aurons le bonheur de nous marier le</p>
        <p class="is-cursive">7 avril 2018</p>
        <p>à la mairie du XIIIème arrondissement de Paris.</p>
      </section>

      <section class="section">
        <h2 class="title is-size-4">Soirée de fête à Casablanca</h2>
        <p>Pour célébrer notre union, rendez-vous le</p>
        <p class="is-cursive">21 avril 2018</p>
        <p>au Maroc. Aidez-nous à festoyer jusqu'au bout de la nuit !</p>
      </section>
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
