<template>
  <div id="app">
    <StartImage />
    <HeroAboutMe />
    <Services />
    <SquareImagesOnLine />
    <ServiceCardCollection />
    <ContactForm />
    <Footer />
  </div>
</template>

<script>
import StartImage from "./components/StartImage.vue";
import HeroAboutMe from "./components/HeroAboutMe.vue";
import SquareImagesOnLine from "./components/SquareImagesOnLine.vue";
import ServiceCardCollection from "./components/ServiceCardCollection.vue";
import ContactForm from "./components/ContactForm.vue";
import Footer from "./components/Footer.vue";
import Services from "./components/Services.vue";

export default {
  name: "app",
  components: {
    StartImage,
    HeroAboutMe,
    SquareImagesOnLine,
    Footer,
    ServiceCardCollection,
    ContactForm,
    Services
  }
};
</script>

<style>
#app {
  font-family: "Quicksand", sans-serif;
  font-weight: 500;
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
  font-weight: 500;
}
</style>
