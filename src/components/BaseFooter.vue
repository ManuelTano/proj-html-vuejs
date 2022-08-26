<template>
  <footer>
    <div class="footertop">
      <div class="container">
        <h6 class="text-white font-italic getintouch">Get in Touch</h6>
        <div id="triangle"></div>
        <div class="row justify-content-between">
          <div class="col-3">
            <h6 class="fw-bold text-white mt-5 text">ABOUT THE BLOG</h6>
            <p class="textfooter mt-2">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque
              fugit, explicabo distinctio sunt, quasi a repellat laborum amet.
            </p>

            <p class="textfooter p-0 m-0">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque
              fugit, explicabo distinctio sunt, quasi a repellat laborum amet.
            </p>

            <h6 class="fw-bold text-white mt-3 text pointer">
              VIEW MORE
              <i class="fa-solid fa-angle-right mx-2 pointer"></i>
            </h6>
          </div>
          <div class="col-3">
            <h6 class="fw-bold text-white mt-5 text">RECENT POSTS</h6>
            <div class="d-flex mt-3">
              <img
                :src="require('@/assets/images/our-office-4-square.jpg')"
                alt=""
                class="w-25"
              />
              <div class="mx-2">
                <h6 class="lightgrey text">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                </h6>
                <span class="grey">12:53 AM Dec 19th</span>
              </div>
            </div>
            <div class="d-flex mt-3">
              <img
                :src="require('@/assets/images/our-office-5-square.jpg')"
                alt=""
                class="w-25"
              />
              <div class="mx-2">
                <h6 class="lightgrey text">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                </h6>
                <span class="grey">12:53 AM Dec 19th</span>
              </div>
            </div>
          </div>
          <div class="col-3">
            <h6 class="fw-bold text-white mt-5 text">RECENT COMMENTS</h6>
            <div class="comment">
              <p class="lightgrey m-0 p-0">
                <i class="fa-solid fa-angle-right mx-2 green"></i>
                <strong>John Doe</strong> commented on
                <b>lorem ipsum dolor sit amet</b>.
              </p>
              <span class="grey">12:53 AM Dec 19th</span>
            </div>
            <div class="mt-4">
              <p class="lightgrey m-0 p-0">
                <i class="fa-solid fa-angle-right mx-2 green"></i>
                <strong>John Doe</strong> commented on
                <b>lorem ipsum dolor sit amet</b>.
              </p>
              <span class="grey">12:53 AM Dec 19th</span>
            </div>
          </div>
          <div class="col-3">
            <h6 class="fw-bold text-white mt-5 text">CATEGORIES</h6>
            <span
              v-for="(tagFooter, index) in tagFooter"
              :key="index"
              class="categories"
            >
              {{ tagFooter }}</span
            >
          </div>
        </div>
      </div>
    </div>

    <div class="footerbottom">
      <div class="container">
        <div class="row">
          <div class="col-6">
            <div class="d-flex">
              <img
                :src="require('@/assets/images/logo-footer.png')"
                alt=""
                class="logo"
              />
              <span class="grey mx-5 mt-2">
                © Copyright 2022. All Rights Reserved.</span
              >
            </div>
          </div>

          <div class="col-6 text-end">
            <span class="grey pointer"
              ><i class="fa-solid fa-angle-right grey mx-2"></i>FAQ's</span
            >
            <span class="grey pointer"
              ><i class="fa-solid fa-angle-right grey mx-2"></i>Sitemap</span
            >
            <span class="grey pointer"
              ><i class="fa-solid fa-angle-right grey mx-2"></i>Contact Us</span
            >
          </div>
        </div>
      </div>
      <a href="#top" class="text-center p-3"><i class="fas fa-chevron-up "></i></a>
    </div>
  </footer>
</template>

<script>
export default {
  name: "BaseFooter",
  props: {
    tagFooter: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "src/assets/sass/style.scss";

.footertop {
  background-color: #212529;
  padding-top: 50px;
  padding-bottom: 80px;
  position: relative;
}
.getintouch {
  position: absolute;
  top: -20px;
  left: 300px;
  background-color: $primary-color;
  font-family: "Shadows Into Light", cursive;
  font-size: 20px;
  padding: 10px 25px;
}

.textfooter {
  font-size: 13px;
  color: grey;
}

.col-3 img {
  border-radius: 50%;
}

.lightgrey {
  color: lightgrey;
  font-size: 14px;
}

.grey {
  color: grey;
  font-size: 13px;
}

.text {
  font-size: 14px;
}

.green {
  color: $primary-color;
}

b {
  color: $primary-color;
  cursor: pointer;
}

.categories {
  background-color: black;
  font-weight: bold;
  font-size: 12px;
  padding: 1px;
  color: white;
  cursor: pointer;
  margin-right: 13px;
  border-radius: 2px solid black;
}

.footerbottom {
  background-color: #1c2023;
  padding-top: 25px;
  padding-bottom: 25px;

  a {
    bottom: 0;
    right: 1%;
    width: 45px;
    height: 30x;
    line-height: 30px;
    position: fixed;
    color: #B3B4B5;
    background: #373839;
    border-radius: 2px;
  }
}

.logo {
  color: grey;
  width: 80px;
}

.pointer {
  cursor: pointer;
}

#triangle {
  width: 0;
  height: 0;
  border-left: 25px solid transparent;
  border-right: 0px solid transparent;
  border-bottom: 20px solid green;
  position: absolute;
  top: -20px;
  left: 275px;
}
</style>