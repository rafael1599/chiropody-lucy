<template>
  <Home msg="Home"/>
  <Services msg="Services"/>
  <Laser msg="Laser"/>
  <Rehab msg="Rehab"/>
</template>

<script>
import Home from './components/Home.vue';
import Services from './components/Services.vue';
import Rehab from './components/Rehab.vue';
import Laser from './components/Laser.vue';

export default {
  name: 'App',
  components: {
    Home,
    Services,
    Laser,
    Rehab,
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

</style>