<!-- HelloWord.vue -->

<template>
  <div class="hello">
    <img src="../assets/harden.jpg">
    <h1>{{ msg }}</h1>
    <nav>
      <router-link to="/">index</router-link>
      <router-link to="/down">link2</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'this is index, Harden stands'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#logo {
  max-width: 60px;
}
</style>
