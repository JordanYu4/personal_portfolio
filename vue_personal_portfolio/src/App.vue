<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Sidebar />

    <div id="wrapper">
      <Intro />      
      <Projects />
      <Skills />
      <HardwarePrototypingSplash />
      <Contact />
    </div>
    
    <Footer />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Sidebar from './components/Sidebar.vue';
import Intro from './components/Intro.vue';
import Projects from './components/Projects.vue';
import Skills from './components/Skills.vue';
import HardwarePrototypingSplash from './components/HardwarePrototypingSplash.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue'; 

export default {
  name: 'app',
  components: {
    Sidebar,
    Intro,
    Projects,
    Skills,
    HardwarePrototypingSplash,
    Contact,
    Footer
  } 
}
</script>

<style>
@import "../../assets/css/main.css";

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
