<script>
import appHeader from "./components/appHeader.vue";
import appJumbo from "./components/appJumbo.vue";
import appMain from "./components/appMain.vue";
import appIcon from "./components/appIcon.vue";
import appFooter from "./components/appFooter.vue";

export default {
  components: { appHeader, appJumbo, appMain, appIcon, appFooter },
};
</script>

<template>
  <div>
    <header>
      <appHeader />
    </header>

    <section>
      <appJumbo />
    </section>

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
@use "./assets/styles/general.scss" as *;
</style>
