<template>
  <div>
    <Header />
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
// Variables
$blue: #0282f9;
$white: #fff;
$black: #1c1c1c;

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
  background: $blue;
}
.bg-white {
  background: $white;
}
.bg-black {
  background: $black;
}
</style>