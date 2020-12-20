<template>
  <div id="app">
    <img src="./assets/logostd.png" style="width: 120px;">
    <Header/>
    <Footer/>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
@import "assets/style.css";

</style>
