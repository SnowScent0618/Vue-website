<template>
  <nav>
    <div class="navbar">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/projects">Projects</router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
.navbar {
  font-family: "Ubuntu";
  font-size: 18px;
  overflow: hidden;
  background-color: #333;
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  background-color: #333;
  padding: 14px 16px;
  text-decoration: none;
  transition: 0.3s;
  position: relative;
  z-index: 2;
  overflow: hidden;
}

.navbar a::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  transition: 0.3s;
  background-color: #fff;
  transform: scale(0);
}

.navbar a:hover {
  color: black;
}

.navbar a:hover::before {
  transform: scale(1);
}

</style>
