<template>
  <div class="footer">
    <div class="footer__top">
      <div class="footer__top__title">
        <div><strong>Zid</strong>App</div>
        <div>Market</div>
      </div>
      <img class="footer__top__logo" src="../../../assets/logo.png" />
    </div>
    <div class="footer__middle">
      <font-awesome-icon
        class="icon"
        :icon="{ prefix: 'fab', iconName: 'twitter' }"
      />
      <font-awesome-icon
        class="icon"
        :icon="{ prefix: 'fab', iconName: 'instagram' }"
      />
      <font-awesome-icon
        class="icon"
        :icon="{ prefix: 'fab', iconName: 'linkedin' }"
      />
      <font-awesome-icon
        class="icon"
        :icon="{ prefix: 'fab', iconName: 'youtube' }"
      />
    </div>
    <div class="footer__bottom">
      <div class="icon msg">
        <font-awesome-icon icon="envelope" />
      </div>
      <div class="icon arrow">
        <font-awesome-icon icon="arrow-up" />
      </div>
    </div>
  </div>
</template>
<script>
import "./footer.scss";
import { library } from "@fortawesome/fontawesome-svg-core";
import { faEnvelope, faArrowUp } from "@fortawesome/free-solid-svg-icons";
import {
  faTwitter,
  faInstagram,
  faYoutube,
  faLinkedin,
} from "@fortawesome/free-brands-svg-icons";
library.add(faEnvelope);
library.add(faArrowUp);
library.add(faLinkedin);
library.add(faTwitter);
library.add(faInstagram);
library.add(faYoutube);
export default {
  name: "Footer",
};
</script>
