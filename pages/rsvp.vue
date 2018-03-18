<template>
  <section class="section has-text-centered">
    <div class="container is-size-5">
      <h1 class="is-size-3 is-cursive">
        Confirmez votre presence
      </h1>
      <section class="section">
        <p>
          Nous vous remercions de nous confirmer votre présence par email :
          <span class="is-cursive">mariage.leila.nassim@gmail.com</span>
        </p>
      </section>
    </div>
  </section>
</template>

<script>
export default {
  transition: 'page',
  head: {
    title: 'Leïla et Nassim | RSVP',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Confirmez votre présence au mariage de Leïla Coquard et Nassim Benkirane'
      }
    ],
    link: [
      { rel: 'canonical', href: 'https://www.leilaetnassim.fr/rsvp' }
    ]
  }
}
</script>
