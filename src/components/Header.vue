<template>
  <div class="bg-white shadow">
    <div class="container">
      <header>
        <img id="header-logo" src="../assets/dc-logo.png" alt="DC LOGO" />
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </header>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
header {
  padding: 20px;
  display: flex;
  justify-content: space-between;
  #header-logo {
    width: 80px;
  }
  ul {
    display: flex;
    align-items: center;
    li {
      list-style-type: none;
      padding: 0 10px;
      a {
        cursor: pointer;
        font-weight: 700;
        text-decoration: none;
        color: #1c1c1c;
      }
    }
  }
}
</style>