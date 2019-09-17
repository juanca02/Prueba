<template>
  <div id="app">
    
    <Head></Head>
    <Footer></Footer>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Head from './components/Head.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Head,
    Footer
  }
}
</script>

<style>

</style>
