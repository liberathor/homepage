<template>
  <div>
    <navbar></navbar>
    <nuxt/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'

  export default {
    components: {
      Navbar
    }
  }
</script>

<style>
  body, html {
    height: 100%;
  }

  body {
    background-image: url("../static/alternative-energy-background-blue-1036936.jpg");
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }

  html {
    font-family: "Helvetica Neue", "Source Sans Pro", Arial, sans-serif;
  }
</style>
