<template>
  <div>
    <Hero/>
    <nuxt ref="page"/>
  </div>
</template>

<script>
import Hero from '~/components/Hero.vue'

export default {
  components: {
    Hero
  }
}
</script>
