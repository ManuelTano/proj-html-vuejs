<template>
  <header>
    <div class="header-top">
      <div class="container">
        <ul class="d-flex py-3 p-0">
          <li v-for="(topNav, index) in topNav" :key="index">
            <a href="" class="minitext">{{ topNav }}</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="header-middle border-bottom">
      <div class="container">
        <figure>
          <img
            :src="require('@/assets/images/logo-default-slim.png')"
            alt=""
            class="py-4"
          />
        </figure>
      </div>
    </div>

    <div class="header-bottom">
      <div class="container">
        <div class="row">
          <div class="col-6">
            <ul class="d-flex py-3 p-0 m-0">
              <li v-for="(bottomNav, index) in bottomNav" :key="index">
                <a href="">{{ bottomNav }}</a>
              </li>
            </ul>
          </div>
          <div class="col-6 text-end">
            <span class="text-black"
              ><i class="fa-solid fa-search mt-3"></i
            ></span>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "BaseHeader",
  props: {
    topNav: Array,
    bottomNav: Array,
  },
};
</script>

<style lang="scss">
@import "src/assets/sass/style.scss";

.header-top {
  background-color: $primary-color;
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

.minitext {
  font-size: 12px;
}
</style>