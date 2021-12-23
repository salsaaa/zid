<template>
  <div class="about">
    <div class="about__title">طور متجرك ووسع آفاق تجارتك مع سوق تطبيقات زد</div>
    <div class="about__sub-title">
      طور تجارتك من خلال تطبيقات وحلول سوق تطبيقات زد التي تساعدك في نمو أرباحك
      عبر إدارة عمليات متجرك بشكل فعال واحترافي
    </div>
    <div>
      <Button text="تصفح التطبيقات" />
    </div>
  </div>
</template>
<script>
import "./about.scss";
import Button from "../../shared/button/button.vue";
export default {
  name: "About",
  components: {
    Button,
  },
};
</script>
