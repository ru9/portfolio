<template>
  <div id="app">
    <StartImage />
    <HeroAboutMe />
  </div>
</template>

<script>
import StartImage from "./components/StartImage.vue";
import HeroAboutMe from "./components/HeroAboutMe.vue";

export default {
  name: "app",
  components: {
    StartImage,
    HeroAboutMe
  }
};
</script>

<style>
#app {
  font-family: "Cardo", serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100%;
  width: 100%;
  max-width: 100vw;
  overflow: hidden;
}
html body {
  max-width: 100vw;
  margin: 0;
  padding: 0;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Oswald", sans-serif;
  text-transform: uppercase;
}
</style>
