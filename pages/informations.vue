<template>
  <section class="section has-text-centered">
    <div class="container is-size-5">
      <h1 class="is-size-3 is-cursive">
        Dates & Lieux du mariage
      </h1>

      <section class="section">
        <h2 class="title is-size-4">Cérémonie de mariage à Paris</h2>

        <p>Nous aurons le bonheur de nous marier le</p>
        <p class="is-cursive">7 avril 2018 à 13h30</p>
        <p>à la mairie du XIIIème arrondissement de Paris.</p>
        <p>La cérémonie sera suivie d'un cocktail</p>
        <iframe
          class="embeded_map"
          frameborder="0" style="border:0"
          :src="`https://www.google.com/maps/embed/v1/place?key=${
            google_api_key
          }&q=Mairie+du+13+e+arrondissement,Paris+France`" allowfullscreen>
        </iframe>
      </section>

      <section class="section">
        <h2 class="title is-size-4">Soirée de fête à Casablanca</h2>
        <p>Pour célébrer notre union, rendez-vous le</p>
        <p class="is-cursive">21 avril 2018 à 20h</p>
        <p>au 109 boulevard de l'Atlantide, à Casablanca (Maroc).</p>
        <p>Aidez nous à festoyer jusqu'au bout de la nuit !</p>
        <iframe
          class="embeded_map"
          frameborder="0" style="border:0"
          :src="`https://www.google.com/maps/embed/v1/place?key=${
            google_api_key
          }&q=109,boulevard+de+l+atlantide,Casablanca+Maroc`" allowfullscreen>
        </iframe>
      </section>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import config from '../config'

export default {
  components: {
    Logo
  },
  data: () => ({
    google_api_key: config.google_api_key
  }),
  transition: 'page'
}
</script>
