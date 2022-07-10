<template>
  <Navbar/>
  <Landing/>
</template>

<script>

import Navbar from './components/Navbar.vue'
import Landing from './components/Landing.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Landing
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
    box-sizing: border-box;
  }

  body {
    background-color: #404040;
  }
</style>
