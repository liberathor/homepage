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

  .background-superear {
    background-image: linear-gradient(rgba(0, 27, 255, 0), rgb(0, 0, 0)), url("../static/grandmother-strikes-again1200x800.jpg");
    background-position: center;
    background-size: cover;
    height: 100%;
  }

  .background-scanery {
    background-image: linear-gradient(rgb(0, 0, 0), rgba(0, 27, 255, 0)), url("../static/ray-rui-729475-unsplash.jpg");
    background-position: center;
    background-size: cover;
    height: 100%;
  }
</style>
