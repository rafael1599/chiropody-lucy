<template>
  <Home msg="Home"/>
  <Services msg="Services"/>
  <Laser msg="Laser"/>
  <Rehab msg="Rehab"/>
  <Catalog/>
  <v-app>
  <Footer msg="Footer"/>
  </v-app>
</template>

<script>
import Home from './components/Home.vue';
import Services from './components/Services.vue';
import Rehab from './components/Rehab.vue';
import Laser from './components/Laser.vue';
import Footer from './components/Footer.vue';
import Catalog from './components/Catalog.vue';

export default {
  name: 'App',
  components: {
    Home,
    Services,
    Laser,
    Rehab,
    Footer,
    Catalog,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}
body{
  background-color: #77B9B4;
}

@import "./assets/style/Card.css";
@import "./assets/style/Home.css";
@import "./assets/style/Text.css";
@import "./assets/style/Services.css";
@import "./assets/style/Footer.css";

</style>