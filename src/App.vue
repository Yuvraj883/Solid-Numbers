<template>
  <Nav id="nav"/>
  <About id="about"/>
  <FAQ id="faq"/>
  <Team id="team"/>
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
/* @import url('./assets/SOLID-NUMBERS/BaronNeue.otf');
@import url('./assets/SOLID-NUMBERS/BaronNeueBold.otf');
@import url('./assets/SOLID-NUMBERS/BaronNeueBoldItalic.otf');
@import url('./assets/SOLID-NUMBERS/BaronNeueItalic.otf');
@import url('./assets/SOLID-NUMBERS/BaronNeueBlackItalic.otf');
@import url('./assets/SOLID-NUMBERS/Oswald-VariableFont_wght.ttf'); */


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  -webkit-scrollbar: none;
 
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
