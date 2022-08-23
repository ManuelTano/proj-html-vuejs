<template>
  <div id="app">
    <header>
      <BaseHeader />
    </header>
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
import BaseHeader from "./components/BaseHeader.vue";
import "./assets/sass/style.scss";
export default {
  name: "App",
  components: {
    BaseHeader,
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
