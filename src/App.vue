<template>
  <div id="app">
    <NavBar/>
    <Slide/>
    <Services/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Slide from './components/Slide.vue';
import Services from './components/Services.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Slide,
    Services
  }
}
</script>

<style>
@import './assets/css/styles.css';
</style>
