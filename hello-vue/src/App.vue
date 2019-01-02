<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <SiteFooter></SiteFooter>
  </div>
</template>

<script>
import SiteFooter from '@/components/SiteFooter'

export default {
  name: 'App',
  components: {
    SiteFooter
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
