<template>
  <section class="row section center-lg middle-lg" id="home">
    <div class="col-lg-6">
      <img src="../assets/hand.svg">
    </div>

    <div class="col-lg-6 start-lg">
      <div class="pl-lg">
        <h1>When they let go, we don't.</h1>
        <DividerLine/>
        <p class="text-col-std">we are orpheus, the future of digital personality resurrection.</p>
        <Button button-text="learn more"/>
      </div>
    </div>
  </section>
</template>

    <script>
import DividerLine from "./DividerLine.vue";
import Button from "./Button";

export default {
  name: "LandingSection",
  components: {
    DividerLine,
    Button
  }
};
</script>