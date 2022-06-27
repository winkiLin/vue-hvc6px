<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="https://vuejs.org/images/logo.png"> -->
    <Index />
  </div>
</template>

<script>
import Index from './components/index.vue';

export default {
  name: 'App',

  components: {
    Index,
  },
};
</script>

<style>
body {
  background: black;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #d7d7d7;
}
</style>
