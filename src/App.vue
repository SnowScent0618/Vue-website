<template>
  <NavBar />
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Ubuntu');
html{
  scroll-behavior: smooth;
}
* {
  box-sizing: border-box;
  font-family: "Ubuntu";
}

body {
  background-color: #202020;
  margin: 0;
  font-size: 22px;
  align-items: center;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>

<script>
import NavBar from '@/components/Navbar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  }
}

</script>
