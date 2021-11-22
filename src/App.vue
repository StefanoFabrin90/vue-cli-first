<template>
  <div id="app">
    <Header />

    <Intro />
    <Intro />
    <Intro />
    <section class="img">
      <img src="./assets/logo.png" alt="">
    </section>
    
    
  </div>
</template>

<script>
import Header from '@/components/header.vue';
import Intro from '@/components/intro.vue';


export default {
  name: 'App',
  components: {
    // posso scrivere anche solo il nome perche uguale Header,
    // Header: Header
    Header,
    Intro,
    

  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
