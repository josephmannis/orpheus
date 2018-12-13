<template>
  <header :class="{'headroom--unpinned': hide}" class="header headroom">
    <div class="row center-lg middle-lg">
      <button class="header-link" v-on:click="scrollToSection('home')">home</button>
      <button class="header-link" v-on:click="scrollToSection('about')">about</button>
      <img class="logo" src="../assets/orpheus-logo.svg">
      <button class="header-link" v-on:click="scrollToSection('services')">services</button>
      <button class="header-link" v-on:click="scrollToSection('reviews')">reviews</button>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      limitPosition: 300,
      hide: false,
      lastPosition: 0
    };
  },
  methods: {
    scrollToSection: function(elemId) {
      document
        .getElementById(elemId)
        .scrollIntoView({ behavior: "smooth", block: "start" });
    },
    handleScroll: function() {
      if (
        this.lastPosition < window.scrollY &&
        this.limitPosition < window.scrollY
      ) {
        this.hide = true;
      }

      if (this.lastPosition > window.scrollY) {
        this.hide = false;
      }

      this.lastPosition = window.scrollY;
    }
  },
  created: function() {
    window.addEventListener("scroll", this.handleScroll);
  },
  destroyed: function() {
    window.removeEventListener("scroll", this.handleScroll);
  }
};
</script>