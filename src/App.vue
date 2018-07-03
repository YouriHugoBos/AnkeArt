<template>
  <div id="app">
	<Navbar/>
	<Home/>
  </div>
</template>

<script>

import Home from './components/Home.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'app',
  components: {
	Navbar,Home
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Raleway');

#app {
  font-family: 'Raleway', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body{
	margin: 0;
}
</style>
