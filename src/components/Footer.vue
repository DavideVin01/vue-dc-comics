<template>
  <footer class="bg-darkgray">
    <div class="container">
      <div class="flex">
        <div class="col">
          <button><a>SIGN-UP NOW!</a></button>
        </div>
        <div class="col">
          <h3>FOLLOW US</h3>
          <ul>
            <li><img src="../assets/footer-facebook.png" alt="Facebook" /></li>
            <li><img src="../assets/footer-twitter.png" alt="Twitter" /></li>
            <li><img src="../assets/footer-youtube.png" alt="YouTube" /></li>
            <li>
              <img src="../assets/footer-pinterest.png" alt="Pinterest" />
            </li>
            <li>
              <img src="../assets/footer-periscope.png" alt="Periscope" />
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
.flex {
  display: flex;
  justify-content: space-between;
}
.col {
  justify-content: space-between;
  display: flex;
  align-items: center;
  h3 {
    color: dodgerblue;
  }
}
footer {
  padding: 30px;
}
ul {
  display: flex;
  padding-left: 15px;
  li {
    list-style-type: none;
    padding: 0 10px;
  }
}
button {
  background-color: transparent;
  border: 1px solid dodgerblue;
  padding: 15px;
  a {
    color: #fff;
    font-size: 18px;
  }
}
</style>