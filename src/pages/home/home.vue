<template>
  <div>
    <Header />
    <About />
    <ZidView />
    <Benefits />
    <SpecialApps />
    <Footer />
  </div>
</template>

<script>
import Header from "../../components/core/header/header.vue";
import Footer from "../../components/core/footer/footer.vue";
import About from "../../components/sections/about/about.vue";
import SpecialApps from "../../components/sections/special-apps/special-apps.vue";
import Benefits from "../../components/sections/benefits/benefits.vue";
import ZidView from "../../components/sections/zid-view/zid-view.vue";
export default {
  name: "Home",
  components: {
    Header,
    About,
    ZidView,
    SpecialApps,
    Footer,
    Benefits,
  },
};
</script>
