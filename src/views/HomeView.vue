<template>
  <NavBar />
  <h1>fj</h1>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NavBar from '@/components/Top.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    NavBar
  }
}
</script>
