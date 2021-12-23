<template>
  <button class="button" :style="{ backgroundColor: bgColor }">
    {{ text }}
    <div class="button__icon">></div>
  </button>
</template>
<script>
import "./button.scss";
export default {
  name: "Button",
  props: {
    text: String,
    bgColor: String,
  },
};
</script>
