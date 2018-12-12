<template>
  <button class="btn">{{buttonText}}</button>
</template>

<script>
export default {
  name: "Button",
  props: {
    buttonText: String
  }
};
</script>
