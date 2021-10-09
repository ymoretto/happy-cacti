<template>
  <div class="wrapper">
    <Navbar />
    <Canvas />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Footer from './components/Footer'
import Canvas from './components/Canvas'

export default {
  name: 'App',

  components: {
    Navbar,
    Footer,
    Canvas,
  }
}
</script>

<style>

*,
*::before,
*::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
  --clr-green: rgb(11, 126, 11);
}

</style>