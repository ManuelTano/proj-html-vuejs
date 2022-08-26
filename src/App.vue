<template>
  <div id="app">
    <header>
      <BaseHeader :topNav="topNav" :bottomNav="bottomNav" />
    </header>
    <main>
      <BaseMain />
    </main>
    <footer>
      <BaseFooter :tagFooter="tagFooter"/>
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
  data() {
    return {
      topNav: [
        "Everything about Lifestyle, Travel and Gadgets!",
        "SIGN IN",
        "ABOUT US",
        "CONTACT US",
        "BUY NOW",
      ],

      bottomNav: [
        "HOME",
        "ELEMENTS",
        "FEATURES",
        "PAGES",
        "PORTFOLIO",
        "BLOG",
        "SHOP",
      ],

      tagFooter: [
        "GADGETS",
        "PHOTOGRAPHY",
        "LIFESTYLE",
        "FASHION",
        "RECIPES",
        "TRAVEL",
        "BUSINESS",
        "ARCHITECTURE",
        "REVIEWS",
        "SPORTS",
        "VIDEOS",
        "TECHNOLOGY",
        "DESIGN",
      ]
    };
  },
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
  font-family: "Poppins", sans-serif;
}
</style>
