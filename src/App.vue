<template>
  <Nav/>
  <About/>
  <FAQ/>
  <Team/>
</template>

<script>
import Nav from './components/Nav.vue';
import About from './components/About.vue';
import FAQ from './components/FAQ.vue'
import Team from './components/Team.vue';

export default {
//eslint-disable-multi-word

  name: 'App',
  components: {
    Nav,
    About,
    Team,
    FAQ
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}
Html{
  margin:0;
  padding:0;
}
body{
  margin:0;
  padding:0;
}
</style>
