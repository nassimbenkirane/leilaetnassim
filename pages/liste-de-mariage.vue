<template>
  <section class="section has-text-centered">
    <div class="container is-size-5">
      <h1 class="is-size-3 is-cursive">
        Voici notre liste de mariage
      </h1>
      <section class="section">
        <a class="button is-primary" href="https://www.ameliste.fr/list/list?site=leilaetnassim" target="_blank">Accéder à notre liste de mariage</a>
      </section>
    </div>
  </section>
</template>

<script>
export default {
  transition: 'page',
  head: {
    title: 'Leïla et Nassim | Liste de mariage',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Voici le lien de la liste de mariage pour Leïla Coquard et Nassim Benkirane'
      }
    ],
    link: [
      { rel: 'canonical', href: 'https://www.leilaetnassim.fr/liste-de-mariage' }
    ]
  }
}
</script>
