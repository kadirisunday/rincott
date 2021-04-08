<template>
  <div id="app">
    <headers></headers>
    <about></about>
    <services></services>
    
    <contact></contact>
    
  
  </div>
</template>

<script>
import Headers from './components/Headers.vue';
import About from './components/About.vue';
import Services from './components/Services';

import Contact from './components/Contact';
// import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    'headers':Headers,
    'about': About,
    'services': Services,
    'contact' : Contact,
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
