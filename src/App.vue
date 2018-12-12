<template>
  <div id="app">
    <Header/>
    <LandingSection/>
    <AboutSection/>
  </div>
</template>

<script>
import Header from "./components/Header";
import LandingSection from "./components/LandingSection";
import AboutSection from "./components/AboutSection";

export default {
  name: "app",
  components: {
    Header,
    LandingSection,
    AboutSection
  }
};
</script>

<style lang="scss">
@import "./css/main.scss";
</style>
