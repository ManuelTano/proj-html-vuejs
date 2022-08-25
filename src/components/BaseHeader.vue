<template>
  <header>
    <div class="header-top">
      <div class="container">
        <ul class="d-flex py-3 pl-0">
          <li>
            <a href="" >Everything about Lifestyle, Travel and Gadgets!</a>
          </li>
          <li><a href="">SIGN IN</a></li>
          <li><a href="">ABOUT US</a></li>
          <li><a href="">CONTACT US</a></li>
          <li><a href="">BUY NOW</a></li>
        </ul>
      </div>
    </div>
    <div class="header-middle border-bottom">
      <div class="container">
        <figure>
          <img :src="require('@/assets/images/logo-default-slim.png')" alt="" class="py-4" />
        </figure>
      </div>
    </div>

    <div class="header-bottom">
        <div class="container">
        <ul class="d-flex py-3 pl-0">
          <li><a href="">HOME</a></li>
          <li><a href="">ELEMENTS</a></li>
          <li><a href="">FEATURES</a></li>
          <li><a href="">PAGES</a></li>
          <li><a href="">PORTFOLIO</a></li>
          <li><a href="">BLOG</a></li>
          <li><a href="">SHOP</a></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "src/assets/sass/style.scss";

.header-top {
  background-color: $bgcontacts-color;
}

ul {
  list-style-type: none;
  padding-left: 0px;

  & li {
    padding-right: 20px;

    & a {
      color: white;
      text-decoration: none;
    }
  }
}

.header-bottom .container ul li a {
    color: black;
    font-weight: bold;
    margin-right: 25px;
}

img {
  width: 120px;
}
</style>