<template>
  <div class="bg-white">
    <div class="container">
      <header>
        <img id="header-logo" src="../assets/dc-logo.png" alt="DC LOGO" />
        <ul>
          <li><a>CHARACTERS</a></li>
          <li><a>COMICS</a></li>
          <li><a>MOVIES</a></li>
          <li><a>TV</a></li>
          <li><a>GAMES</a></li>
          <li><a>COLLECTIBLES</a></li>
          <li><a>VIDEOS</a></li>
          <li><a>FANS</a></li>
          <li><a>NEWS</a></li>
          <li><a>SHOP</a></li>
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
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  #header-logo {
    width: 100px;
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
      }
    }
  }
}
</style>