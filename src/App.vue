<template>
  <div id="app">
    <HelloWorld />
    <Certificate />
    <Portfolio />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Certificate from './components/Certificate.vue'
import Portfolio from './components/Portfolio.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Certificate,
    Portfolio
  }
}
</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

* {
  padding: 0;
  margin: 0;
}
#app {
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;

}
</style>
