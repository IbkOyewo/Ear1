<template>
  <div id="app">
    <Navbar/>
    <FirstSection/>
    <SecondSection/>
    <ThirdSection/>
    <FourthSection/>
    <FifthSection/>
    <SixthSection/>
    <Footer/>
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    
  </div>
</template>

<script>

// import HelloWorld from "./components/HelloWorld.vue";
import Navbar from "./components/Navbar.vue";
import FirstSection from './components/FirstSection.vue';
import SecondSection from './components/SecondSection.vue';
import ThirdSection from './components/ThirdSection.vue';
import FourthSection from './components/FourthSection.vue';
import FifthSection from './components/FifthSection.vue';
import SixthSection from './components/SixthSection.vue';
import Footer from './components/Footer.vue';

export default {
  name: "App",
  components: {
    // HelloWorld,
    Navbar,
    FirstSection,
    SecondSection,
    ThirdSection,
    FourthSection,
    FifthSection,
    SixthSection,
    Footer
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  margin-top: 54px;
}
</style>
