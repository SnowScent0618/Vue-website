<template>
  <header>
    <h1 id="heading">{{ message }}</h1>
  </header>
</template>

<script>
export default {
  name: 'Heading',
  props: {
    message: String
  }
}
</script>

<style>
* {
  font-family: "Ubuntu";
}

#heading {
  color: #ffffff;
  text-align: center;
  padding: 20px;
  border-radius: 25px;
}
</style>
