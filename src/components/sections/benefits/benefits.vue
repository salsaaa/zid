<template>
  <div class="benefits">
    <div class="benefits__right">
      <div class="benefits__right__title">
        كل ما تحتاجه لنمو متجرك فى مكان واحد
      </div>
      <div class="benefits__right__sub-title">
        مميزات سوق تطبيقات زد تساعدك في سهولة وسرعة الاستفادة من خدمات وحلول
      </div>
      <div class="benefits__right__sub-title">
        سوق التطبيقات لنمو متجرك ومضاعفة أرباحك
      </div>
      <div class="benefits__right__item">
        <div class="icon"><img src="../../../assets/benefit1.png" /></div>
        <div>سهولة ادارة و تفعيل تطبيقاتك من نفس لوحة تحكم متجرك</div>
      </div>
      <div class="benefits__right__item">
        <div class="icon"><img src="../../../assets/benefit2.png" /></div>
        <div>دعم فني و تقني متكامل متوفر على مدار الساعة</div>
      </div>
      <div class="benefits__right__item">
        <div class="icon"><img src="../../../assets/benefit3.png" /></div>
        <div>أسعار تنافسية مع تجربة مجانية وباقات اشتراك متنوعة</div>
      </div>
      <div class="benefits__right__btn"><Button text="تصفح التطبيقات" /></div>
    </div>
    <div class="benefits__left">
      <Slider source="benefits.gif" />
    </div>
  </div>
</template>
<script>
import "./benefits.scss";
import Slider from "../../shared/slider/slider.vue";
import Button from "../../shared/button/button.vue";
export default {
  name: "Benefits",
  components: {
    Slider,
    Button,
  },
};
</script>
