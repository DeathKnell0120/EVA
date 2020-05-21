<template>
  <div id="app">
    <BarNav></BarNav>
    <img alt="Vue logo" src="./assets/evitaxd.jpg" id="estaimg">
    <div id="micompo"><HelloWorld align="center" msg="No importa que tan difícil o imposible sea, no le pierdas la vista a tu objetivo"/></div>
    <Services></Services>
    <MiComponente id="misRedes"></MiComponente>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/MiComponente.vue'
import BarNav from './components/BarNav.vue'
import Services from './components/Services.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente,
    BarNav,
    Services
  }
}
</script>

<style>
@import './assets/css/styles.css';
@import './assets/css/contact-compi.css';
</style>
