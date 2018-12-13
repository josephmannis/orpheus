<template>
  <div id="app">
    <Header/>
    <LandingSection/>
    <AboutSection/>
    <ServiceSection/>
    <ReviewSection/>
  </div>
</template>

<script>
import Header from "./components/Header";
import LandingSection from "./components/LandingSection";
import AboutSection from "./components/AboutSection";
import ServiceSection from "./components/ServiceSection";
import ReviewSection from "./components/ReviewSection";

export default {
  name: "app",
  components: {
    Header,
    LandingSection,
    AboutSection,
    ServiceSection,
    ReviewSection
  }
};
</script>

<style lang="scss">
@import "./css/main.scss";
</style>
