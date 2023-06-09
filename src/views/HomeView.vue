<template>
  <NavBar />
  <Hero />
  <Featured />
  <Products />
  <Footer />
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/Top.vue'
import Hero from '@/components/Hero.vue'
import Featured from '@/components/Featured.vue'
import Products from '@/components/Products.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    Hero,
    Featured,
    Products,
    Footer
  }
}
</script>
