<script>
import appHeader from "./components/appHeader.vue";
import appMain from "./components/appMain.vue";
import appIcon from "./components/appIcon.vue";
import appFooter from "./components/appFooter.vue";

export default {
  components: { appHeader, appMain, appFooter, appIcon },
};
</script>

<template>
  <div>
    <header>
      <appHeader />
    </header>

    <main>
      <appMain />
    </main>

    <section>
      <appIcon />
    </section>

    <footer>
      <appFooter />
    </footer>
  </div>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap");

body {
  background-color: grey;
  font-family: "Roboto", sans-serif;
}
</style>
