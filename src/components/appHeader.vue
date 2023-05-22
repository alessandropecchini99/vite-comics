<script>
import propMenu from "./navbarVoice.vue";

export default {
  data() {
    return {
      arrMenuVoice: [
        `CHARACTERS`,
        `COMIC`,
        `MOVIES`,
        `TV`,
        `GAMES`,
        `COLLECTIBLES`,
        `VIDEOS`,
        `FANS`,
        `NEWS`,
        `SHOP`,
      ],
    };
  },
  components: {
    propMenu,
  },
};
</script>

<template>
  <div class="section">
    <div class="container">
      <div class="logo">
        <img src="/src/assets/img/dc-logo.png" alt="logo" />
      </div>
      <div class="navbar">
        <ul>
          <propMenu v-for="nav in arrMenuVoice" :key="nav" :menuVoice="nav" />
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/variables.scss" as *;
$DC_color: #0c7cec;

.section {
  height: 110px;
  background-color: white;
  z-index: 90;

  .container {
    @include myContainer;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .logo {
    height: 100%;
    display: flex;
    align-items: center;

    img {
      height: 75%;
      border-radius: 90%;
      &:hover {
        cursor: pointer;
      }
    }
  }

  .navbar {
    height: 100%;

    ul {
      height: 100%;
      display: flex;
      list-style-type: none;
      gap: 1.5em;
      font-weight: 400;
    }
  }
}
</style>
