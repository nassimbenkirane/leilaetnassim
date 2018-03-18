<template>
  <section class="section has-text-centered">
    <div class="container is-size-5">
      <logo/>
      <h2 class="title is-size-3 has-text-weight-normal is-cursive">
        Bienvenue sur le site de notre mariage !
      </h2>
      <p>
        Nous sommes ravis de vous compter parmi nos invités <br>
        et de partager avec vous ce moment de bonheur
      </p>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  transition: 'page',
  head: {
    title: 'Leïla et Nassim | Accueil',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Bienvenue sue le site du mariage de Leïla Coquard et Nassim Benkirane. Le 07 avril 2018 et le 21 avril 2018'
      }
    ],
    link: [
      { rel: 'canonical', href: 'https://www.leilaetnassim.fr' }
    ]
  }
}
</script>
