<template>
  <h2>counter {{ counter }}</h2>
  <button @click="counter++">+</button>
  <button @click= "counter--">-</button>
</template>

<script>

export default {
  name: 'App',
  data(){
    return {
      counter : 0
    }
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
