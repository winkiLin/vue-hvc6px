<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="https://vuejs.org/images/logo.png"> -->
    <Login />
  </div>
</template>

<script>
import Login from './components/login.vue';

export default {
  name: 'App',

  components: {
    Login,
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
  margin-top: 60px;
}
</style>
