<template>
  <div id="links">
    <div class="container">
      <div class="links-box">
        <div class="single-column">
          <ul id="dc-comics">
            <li><h3>DC COMICS</h3></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <ul id="shop">
            <li><h3>SHOP</h3></li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
      </div>
      <div class="links-box">
        <ul id="dc">
          <li><h3>DC</h3></li>
          <li><a href="#">Terms Of Use</a></li>
          <li><a href="#">Privacy policy (new)</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Subscriptions</a></li>
          <li><a href="#">Talent Workshops</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Ratings</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>
      <div class="links-box">
        <ul id="sites">
          <li><h3>SITES</h3></li>
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Power Visa</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Links",
};
</script>

<style scoped lang="scss">
.container {
  background-image: url("../assets/dc-logo-bg.png");
  background-repeat: no-repeat;
  background-position: right;
  width: 100%;
}

.single-column {
  display: flex;
  flex-direction: column;
  ul {
    margin: 0 0 20px 0;
  }
}

.links-box {
  padding: 60px 20px;
}

#links {
  background-image: url("../assets/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  //   height: 400px;
  //   flex-grow: 1;
  display: flex;
  color: #fff;
}
div {
  display: flex;
}
h3 {
  padding: 0 0 10px 0;
}

li {
  list-style-type: none;
}
a {
  color: rgb(165, 165, 165);
  text-decoration: none;
}
</style>