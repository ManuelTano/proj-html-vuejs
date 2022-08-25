<template>
  <div id="app">
    <header>
      <BaseHeader />
    </header>
    <main>
      <BaseMain />
    </main>
    <footer>
      <BaseFooter />
    </footer>
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import BaseMain from "./components/BaseMain.vue";
import BaseFooter from "./components/BaseFooter.vue";
import "./assets/sass/style.scss";
export default {
  name: "App",
  components: {
    BaseHeader,
    BaseMain,
    BaseFooter,
  },
};
</script>

<style lang="scss">
body {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
