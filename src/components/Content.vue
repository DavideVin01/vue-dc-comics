<template>
  <div id="content" class="bg-black">
    <div class="container"></div>
  </div>
</template>

<script>
export default {
  name: "Content",
};
</script>

<style scoped lang="scss">
#content {
  padding: 50px;
  text-align: center;
  background-image: url("../assets/jumbotron.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: top center;
  height: 40vh;
}
h3 {
  color: white;
}
</style>