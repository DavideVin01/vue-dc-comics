<template>
  <div id="shop" class="bg-blue shadow">
    <div class="container">
      <ul>
        <li v-for="item in items" :key="item.text">
          <figure role="button" class="grow">
            <img
              :src="require(`../assets/${item.url}`)"
              :alt="item.description"
            />
            <span class="li-text">{{ item.text }}</span>
          </figure>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Shop",
  data() {
    return {
      items: [
        {
          text: "DIGITAL COMICS",
          description: "DIGITAL COMICS",
          url: "buy-comics-digital-comics.png",
        },
        {
          text: "DC MERCHANDISE",
          description: "DC MERCHANDISE",
          url: "buy-comics-merchandise.png",
        },
        {
          text: "SUBSCRIPTION",
          description: "SUBSCRIPTION",
          url: "buy-comics-subscriptions.png",
        },
        {
          text: "COMIC SHOP LOCATOR",
          description: "COMIC SHOP LOCATOR",
          url: "buy-comics-shop-locator.png",
        },
        {
          text: "DC POWER VISA",
          description: "DC POWER VISA",
          url: "buy-dc-power-visa.svg",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
#shop {
  padding: 30px;
  color: #fff;
}

ul {
  display: flex;
  justify-content: space-around;
  margin-bottom: 0;
  li {
    list-style-type: none;
    figure {
      display: flex;
      align-items: center;
      color: #fff;
      margin-bottom: 0;
      font-weight: 500;
    }
    img {
      max-width: 60px;
      height: 50px;
      padding-right: 10px;
    }
  }
}
// .drop-shadow {
//   box-shadow: 0;
//   transition: box-shadow 1s;
//   &:hover {
//     box-shadow: 0px 0px 2px 0 rgb(81, 177, 255);
//     transition: box-shadow 0.3s ease-in-out;
//   }
// }
.grow {
  transition: scale 0.5s 0.2s ease;
  &:hover {
    transform: scale(1.1);
  }
}
</style>