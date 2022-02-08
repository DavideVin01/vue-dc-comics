<template>
  <div>
    <Header />
    <Content />
    <Shop />
    <Links />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import Shop from "./components/Shop.vue";
import Links from "./components/Links.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Content,
    Shop,
    Links,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>