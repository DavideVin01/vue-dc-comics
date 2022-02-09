<template>
  <footer class="bg-darkgray">
    <div class="container">
      <div class="flex">
        <div class="column">
          <button><a>SIGN-UP NOW!</a></button>
        </div>
        <div class="column d-flex align-items-center" role="button">
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
.column {
  display: flex;
  justify-content: space-between;
  h3 {
    color: dodgerblue;
    font-size: 22px;
    margin-bottom: 0;
  }
}
footer {
  padding: 30px;
}
ul {
  display: flex;
  padding-left: 15px;
  margin-bottom: 0;
  li {
    list-style-type: none;
    padding: 0 10px;
  }
}
button {
  background-color: transparent;
  border: 1px solid dodgerblue;
  margin-left: 40px;
  padding: 15px;
  color: #fff;
  font-size: 18px;
}
</style>