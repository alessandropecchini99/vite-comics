<script>
export default {};
</script>

<template>
  <div class="body">
    <div class="container">
      <div class="logo">
        <img src="/public/img/dc-logo.png" alt="logo" />
      </div>
      <div class="navbar">
        <ul>
          <li>CHARACTERS</li>
          <li>COMICS</li>
          <li>MOVIES</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>COLLECTIBILES</li>
          <li>VIDEOS</li>
          <li>FANS</li>
          <li>NEWS</li>
          <li>SHOP</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
$DC_color: #0c7cec;

.body {
  height: 10vh;
  background-color: white;

  .container {
    height: 100%;
    width: 80%;
    margin-inline: auto;
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

      li {
        display: flex;
        align-items: center;

        &:hover {
          color: $DC_color;
          border-bottom: 5px $DC_color solid;
        }
      }
    }
  }
}
</style>
