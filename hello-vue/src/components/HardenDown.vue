<!-- HardenDown.vue -->

<template>
  <div class="hello">
    <img src="../assets/harden.jpg">
    <h1>{{ msg }}</h1>
    <nav>
      <router-link to="/">index</router-link>
      <router-link to="/down">link2</router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HardenDown',
  data () {
    return {
      msg: 'this is link two, Harden lying down'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello img {
  transform: perspective(600px) rotateX(80deg);
}
</style>
