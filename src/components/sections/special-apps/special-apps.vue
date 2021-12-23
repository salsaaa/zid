<template>
  <div class="special-apps">
    <div class="special-apps__title">التطبيقات المميزة</div>
    <div class="special-apps__sub-title">
      تطبيقات تقدم حلول وخدمات مميزة نوصي بتجربتها
    </div>
    <div class="special-apps__cards">
      <AppCard />
      <AppCard />
      <AppCard />
      <AppCard />
    </div>
    <div class="special-apps__btn">
      <Button text="جميع التطبيقات" bgColor="transparent" />
    </div>
  </div>
</template>
<script>
import "./special-apps.scss";
import Button from "../../shared/button/button.vue";
import AppCard from "../../cards/app-card/app-card.vue";
export default {
  name: "SpecialApps",
  components: {
    Button,
    AppCard,
  },
};
</script>
