<template>
<div class="main">
  <Navbar />
    witam we vue
  witam we vue
  witam we vue
  <Footer />
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
export default{
  name: 'App',
  components: {
    Navbar, Footer
  }
}
</script>

<style>
#app {
  margin: 0;
  padding: 0;
  margin-top: 8em;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-bottom: 8em;
}
</style>
