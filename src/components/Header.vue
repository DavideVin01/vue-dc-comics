<template>
  <div class="bg-white shadow">
    <div class="container">
      <header>
        <img id="header-logo" src="../assets/dc-logo.png" alt="DC LOGO" />
        <ul>
          <li v-for="link in links" :key="link.text">
            <a :class="{ active: link.active }" :href="link.url">{{
              link.text
            }}</a>
          </li>
        </ul>
      </header>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          text: "CHARACTERS",
          url: "#",
          active: false,
        },
        {
          text: "COMICS",
          url: "#",
          active: true,
        },
        {
          text: "MOVIES",
          url: "#",
          active: false,
        },
        {
          text: "TV",
          url: "#",
          active: false,
        },
        {
          text: "GAMES",
          url: "#",
          active: false,
        },
        {
          text: "COLLECTIBLES",
          url: "#",
          active: false,
        },
        {
          text: "VIDEOS",
          url: "#",
          active: false,
        },
        {
          text: "FANS",
          url: "#",
          active: false,
        },
        {
          text: "NEWS",
          url: "#",
          active: false,
        },
        {
          text: "SHOP",
          url: "#",
          active: false,
        },
      ],
    };
  },
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
        &:active,
        &:hover {
          color: dodgerblue;
        }
      }
      .active {
        color: dodgerblue;
        padding-bottom: 44px;
        border-bottom: 5px solid dodgerblue;
      }
    }
  }
}
</style>