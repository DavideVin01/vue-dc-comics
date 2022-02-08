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
// Variables
$blue: #0282f9;
$white: #fff;
$black: #1c1c1c;
$darkgray: #303030;

$font-marvel: "Marvel", sans-serif;

// Presets
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

// Utilities
body {
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}

// Text Colors
.text-blue {
  color: $blue;
}
.text-white {
  color: $white;
}
.text-black {
  color: $black;
}

// Background Colors
.bg-blue {
  background: #0282f9;
}
.bg-white {
  background: #fff;
}
.bg-black {
  background: #1c1c1c;
}
.bg-darkgray {
  background: #303030;
}
</style>