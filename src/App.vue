<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer />
  </div>
</template>

<script>
import Header from './layouts/Header.vue'
import Main from './layouts/Main.vue'
import Footer from './layouts/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
  * {
     margin: 0;
     padding: 0;
     background-color: black;
     font-family: 'Signika', sans-serif;
  }


</style>
