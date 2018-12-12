<template>
  <section class="row section center-lg middle-lg">
    <div class="col-lg-6 start-lg">
      <div class="pl-lg">
        <h1 class="m-0">A person is their data.</h1>
        <h1 class="mt-0 italic">Let's use that.</h1>
        <DividerLine/>
        <p>
          orpheus develops the most advanced neural networks
          on the market. with help from one of our expert data specialists, we can create a near perfect replica of their personality that you can interact with - as if they were never gone.
        </p>
      </div>
    </div>

    <div class="col-lg-6">
      <img class="phone" src="../assets/phone.svg">
    </div>
  </section>
</template>

<script>
import DividerLine from "./DividerLine.vue";
export default {
  name: "AboutSection",
  components: { DividerLine }
};
</script>

<style>
</style>
