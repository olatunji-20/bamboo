<template>
  <NavBar />
  <Hero />
  <Featured />
  <Footer />
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/Top.vue'
import Hero from '@/components/Hero.vue'
import Featured from '@/components/Featured.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    Hero,
    Featured,
    Footer
  }
}
</script>
