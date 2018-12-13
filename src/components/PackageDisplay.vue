<template>
  <div class="package">
    <div class="package-content">
      <p class="italic bold font-secondary">{{title}} package</p>
      <p class="font-primary color-primary">{{price}} / month</p>
      <p class="font-primary">{{description}}</p>
      <Button button-text="select"/>
    </div>
  </div>
</template>

<script>
import Button from "./Button";
export default {
  name: "PackageDisplay",
  props: {
    title: String,
    price: Number,
    description: String
  },
  components: {
    Button
  }
};
</script>

<style>
</style>
