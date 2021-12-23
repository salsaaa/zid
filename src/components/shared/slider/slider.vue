<template>
  <div class="slider">
    <img class="slider__pattern" src="../../../assets/Dot-Pattern.png" />
    <div>
      <img class="slider__square" :src="require(`@/assets/${source}`)" />
    </div>
    <div class="slider__circle"></div>
  </div>
</template>
<script>
import "./slider.scss";
export default {
  name: "Slider",
  props: {
    source: String,
  },
};
</script>
