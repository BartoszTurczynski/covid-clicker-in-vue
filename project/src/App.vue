<template>
<div class="main">
  <Navbar />
    witam we vue
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
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
* {
margin: 0;
padding: 0;
}


#app {
  margin-top: 7.9em;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-bottom: 6.3em;
  background-image: linear-gradient(90deg, rgba(226,184,31,1) 0%, rgba(255,85,85,1) 49%, rgba(252,176,69,1) 100%);;
}

  /* width */
::-webkit-scrollbar {
  width: 10px;
  background-color: darkred;
}

/* Track */
::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px grey; 
  border-radius: 10px;
}
 
/* Handle */
::-webkit-scrollbar-thumb {
  background: black; 
  border-radius: 10px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: rgb(32, 16, 16); 
}

</style>
