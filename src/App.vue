<template>
  <div id="app">
    <h1></h1>
    <v-main-wrapper></v-main-wrapper>
  </div>
</template>

<script>
import vMainWrapper from './components/V-main-wrapper.vue';



export default {
  name: 'App',
  components: {
    vMainWrapper
  },
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
