<template>
  <Navbar></Navbar>
  <div my=4>
    <ProductProfile></ProductProfile>
  </div>
 
</template>

<script>
import Navbar from './components/Navbar.vue'
import ProductProfile from './components/ProductProfile.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    ProductProfile
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
