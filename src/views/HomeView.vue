<template>
  <NavBar />
  <Hero />
  <Featured />
  <h1>fj</h1>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NavBar from '@/components/Top.vue'
import Hero from '@/components/Hero.vue'
import Featured from '@/components/Featured.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    NavBar,
    Hero,
    Featured
  }
}
</script>
