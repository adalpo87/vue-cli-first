<template>

  <div id="app">

     <Title />

     <Hero />

     <Footer />

  </div>

</template>

<script>

  import Title from '@/components/Title.vue'
  import Hero from '@/components/Hero.vue'
  import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero,
    Footer
  }
}
</script>

<style lang="scs">



</style>
