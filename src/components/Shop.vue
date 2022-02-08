<template>
  <div id="shop" class="bg-blue">
    <div class="container">
      <ul>
        <li>
          <a href="#">
            <img
              src="../assets/buy-comics-digital-comics.png"
              alt="Digital Comics"
            />
            <span class="li-text">DIGITAL COMICS</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-merchandise.png" alt="" />
            <span class="li-text">DC MERCHANDISE</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-subscriptions.png" alt="" />
            <span class="li-text">SUBSCRIPTION</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-comics-shop-locator.png" alt="" />
            <span class="li-text">COMIC SHOP LOCATOR</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/buy-dc-power-visa.svg" alt="" />
            <span class="li-text">DIGITAL COMICS</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Shop",
};
</script>

<style scoped lang="scss">
#shop {
  padding: 30px;
  color: #fff;
  box-shadow: 0 2px 25px 0 black;
}

ul {
  display: flex;
  justify-content: space-around;
}
li {
  list-style-type: none;
  a {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: #fff;
  }
  img {
    max-width: 60px;
    height: 50px;
    padding-right: 10px;
  }
}
</style>