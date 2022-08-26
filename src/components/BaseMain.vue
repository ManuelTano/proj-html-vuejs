<template>
  <main>
    <section id="grey">
      <div class="container">
        <div class="row h-100">
          <div class="col-4 my-3 relative">
            <img
              :src="require('@/assets/images/blog-46.jpg')"
              alt=""
              class="bright"
            />
            <div class="categories">
              <span class="text-white fw-bold subtitle">PHOTOGRAPHY</span>
            </div>
            <h5 class="toptitle px-3">
              How To Take Better Concert Pictures in 30 Seconds
            </h5>
            <p class="sottotitolo">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
              Nam  euismod odio, gravida pelle...
            </p>
          </div>
          <div class="col-4 my-3 relative">
            <img
              :src="require('@/assets/images/blog-47.jpg')"
              alt=""
              class="bright"
            />
            <div class="categories">
              <span class="text-white fw-bold subtitle">GADGETS</span>
            </div>
            <h5 class="toptitle px-3">
              Gadgets That Make Your Smartphone Even Smarter
            </h5>
            <p class="sottotitolo">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
              Nam  euismod odio, gravida pelle...
            </p>
          </div>
          <div class="col-4 my-3 relative">
            <img
              :src="require('@/assets/images/blog-48.jpg')"
              alt=""
              class="bright"
            />
            <div class="categories">
              <span class="text-white fw-bold subtitle">TRAVEL</span>
            </div>
            <h5 class="toptitle px-3">
              20 Top-Rated Tourist Attractions in Manhattan
            </h5>
            <p class="sottotitolo">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
               euismod odio, gravida pelle...
            </p>
          </div>
          <div class="col-4 my-3 relative">
            <img
              :src="require('@/assets/images/blog-49.jpg')"
              alt=""
              class="bright"
            />
            <div class="bottom-categories">
              <span class="text-white fw-bold subtitle">LIFESTYLE</span>
            </div>
            <h5 class="toptitle px-3">The Best Way to Ride a Motorcycle</h5>
            <p class="sottotitolo">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
               euismod odio, gravida pelle...
            </p>
          </div>
          <div class="col-4 my-3 relative">
            <img
              :src="require('@/assets/images/blog-50.jpg')"
              alt=""
              class="bright"
            />
            <div class="bottom-categories">
              <span class="text-white fw-bold subtitle">TRAVEL</span>
            </div>
            <h5 class="toptitle px-3">5 Fun Things to Do at the Beach</h5>
            <p class="sottotitolo">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
               euismod odio, gravida pelle...
            </p>
          </div>
          <div class="col-4 my-3 relative">
            <img
              :src="require('@/assets/images/blog-51.jpg')"
              alt=""
              class="bright"
            />
            <div class="categories">
              <span class="text-white fw-bold subtitle">RECIPES</span>
            </div>
            <h5 class="toptitle px-3">
              Amazingly Fresh Fruit And Herb Drinks For Summer
            </h5>
            <p class="sottotitolo">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
               euismod odio, gravida pelle...
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- SEZIONE POST -->

    <section id="post">
      <div class="container">
        <div class="row">
          <div class="col-4">
            <h5 class="fw-bold">POPULAR POSTS</h5>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-55.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >Simple Ways to Have a Pretty Face</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-56.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >Ranking the greatest players in basketball</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-57.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >4 Ways to Look Cool in Glasses</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-58.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >Top Camper Trailer Towing Tips</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-59.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black">5 Lovely Walks in New York</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
          </div>

          <!-- RECENT POSTS -->

          <div class="col-4">
            <h5 class="fw-bold">RECENT POSTS</h5>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-65.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >Main Reasons To Stop Texting And Driving</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-66a.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >Tips to Help You Quicly Prepare your Lunch</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-67.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >Why should I buy a smartwatch?</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex border-bottom py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-68.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >The best augmented reality smartglasses</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
            <div class="posts d-flex py-3">
              <div class="post-image">
                <img :src="require('@/assets/images/blog-69.jpg')" alt="" />
              </div>
              <div class="post-description">
                <span class="mx-2 text-black"
                  >12 Healthiest Foods to Eat for Breakfast</span
                ><br />
                <span class="mx-2 date">January 12, 2019</span>
              </div>
            </div>
          </div>
          <div class="col-4 relative">
            <h5 class="fw-bold mb-3">FEATURED POSTS</h5>
            <img
              :src="require('@/assets/images/blog-66.jpg')"
              alt=""
              class="bright"
            />
            <div class="minicategories">
              <span class="text-white fw-bold subtitle">RECIPES</span>
            </div>
            <h5 class="minititle px-3">
              Tips to Help You Quickly Prepare your Lunch
            </h5>
            <p class="sidetitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
               euismod odio, gravida pelle...
            </p>
            <h5 class="fw-bold mt-3">FEATURED AUTHOR</h5>
            <div class="posts d-flex my-3 ">
              <div class="image">
                <img :src="require('@/assets/images/avatar.jpg')" alt="" id="light"/>
              </div>
              <div class="post-description">
                <h5 class="mx-3 mt-2 text-black fw-bold">John Doe</h5>
                <p class="mx-3 date grey">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
                  viverra euismod odio, gravida pelle, consectetur adipiscing
                  elit.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="green">
      <div class="container">
        <div class="row justify-content-between">
          <div class="col-1 py-3 pointer">
            <i class="fa-solid fa-angle-left"></i>
          </div>
          <div class="col text-center bg-dark mx-3 py-3 pointer frame">
            <span class="fw-bold text-white">GADGETS</span>
          </div>
          <div class="col text-center bg-dark mx-3 py-3 pointer frame">
            <span class="fw-bold text-white">PHOTOGRAPHY</span>
          </div>
          <div class="col text-center bg-dark mx-3 py-3 pointer frame">
            <span class="fw-bold text-white">LIFESTYLE</span>
          </div>
          <div class="col text-center bg-dark mx-3 py-3 pointer frame">
            <span class="fw-bold text-white">FASHION</span>
          </div>
          <div class="col text-center bg-dark mx-3 py-3 pointer frame">
            <span class="fw-bold text-white">RECIPES</span>
          </div>
          <div class="col text-center bg-dark mx-3 py-3 pointer frame">
            <span class="fw-bold text-white">TRAVEL</span>
          </div>
          <div class="col-1 text-end py-3 pointer">
            <i class="fa-solid fa-angle-right"></i>
          </div>
        </div>
      </div>
    </section>

    <section id="blog">
      <div class="container">
        <div class="row">
          <div class="col-9 py-3">
            <article class="border-bottom py-4">
              <img :src="require('@/assets/images/blog-54.jpg')" alt="" />
              <div class="info d-flex">
                <div class="date d-flex flex-column mt-3">
                  <span class="day fw-bold text-center">12</span>
                  <span class="month fw-bold text-white text-center">JAN</span>
                </div>
                <div class="title mx-3 mt-3">
                  <h3>How to Make Friends as a Grown-up</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nesciunt corporis adipisci repellat maiores eum cupiditate
                    aut molestiae modi, nulla explicabo quo fugit doloremque
                    voluptatem quasi deleniti. Adipisci eveniet omnis harum,
                    nulla explicabo quo fugit doloremque voluptatem quasi
                    deleniti! Proin rhoncus consequat nisl, eu ornare mauris
                    tincidunt vitae. [...]
                  </p>
                </div>
              </div>
              <div class="row readable justify-content-between">
                <div class="col-6">
                  <span
                    ><i class="fa-regular fa-user mx-1"></i>By John Doe</span
                  >
                  <span class="mx-3"
                    ><i class="fa-regular fa-folder mx-1"></i>Lifestyle,
                    Travel</span
                  >
                  <span
                    ><i class="fa-regular fa-comments mx-1"></i>12
                    Comments</span
                  >
                </div>
                <div class="col-2 align-items-end text-end">
                  <div class="button text-center">READ MORE</div>
                </div>
              </div>
            </article>
            <article class="margin border-bottom py-4">
              <img :src="require('@/assets/images/blog-55a.jpg')" alt="" />
              <div class="info d-flex">
                <div class="date d-flex flex-column mt-3">
                  <span class="day fw-bold text-center">12</span>
                  <span class="month fw-bold text-white text-center">JAN</span>
                </div>
                <div class="title mx-3 mt-3">
                  <h3>Simple Ways to Have a Pretty Face</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nesciunt corporis adipisci repellat maiores eum cupiditate
                    aut molestiae modi, nulla explicabo quo fugit doloremque
                    voluptatem quasi deleniti. Adipisci eveniet omnis harum,
                    nulla explicabo quo fugit doloremque voluptatem quasi
                    deleniti! Proin rhoncus consequat nisl, eu ornare mauris
                    tincidunt vitae. [...]
                  </p>
                </div>
              </div>
              <div class="row justify-content-between readable">
                <div class="col-6">
                  <span
                    ><i class="fa-regular fa-user mx-1"></i>By John Doe</span
                  >
                  <span class="mx-3"
                    ><i class="fa-regular fa-folder mx-1"></i>Photography,
                    Travel</span
                  >
                  <span
                    ><i class="fa-regular fa-comments mx-1"></i>12
                    Comments</span
                  >
                </div>
                <div class="col-2 align-items-end text-end">
                  <div class="button text-center">READ MORE</div>
                </div>
              </div>
            </article>
            <article class="margin border-bottom py-4">
              <img :src="require('@/assets/images/blog-56b.jpg')" alt="" />
              <div class="info d-flex">
                <div class="date d-flex flex-column mt-3">
                  <span class="day fw-bold text-center">12</span>
                  <span class="month fw-bold text-white text-center">JAN</span>
                </div>
                <div class="title mx-3 mt-3">
                  <h3>Ranking the greatest players in basketball</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nesciunt corporis adipisci repellat maiores eum cupiditate
                    aut molestiae modi, nulla explicabo quo fugit doloremque
                    voluptatem quasi deleniti. Adipisci eveniet omnis harum,
                    nulla explicabo quo fugit doloremque voluptatem quasi
                    deleniti! Proin rhoncus consequat nisl, eu ornare mauris
                    tincidunt vitae. [...]
                  </p>
                </div>
              </div>
              <div class="row justify-content-between readable">
                <div class="col-6">
                  <span
                    ><i class="fa-regular fa-user mx-1"></i>By John Doe</span
                  >
                  <span class="mx-3"
                    ><i class="fa-regular fa-folder mx-1"></i>Sport,
                    Business</span
                  >
                  <span
                    ><i class="fa-regular fa-comments mx-1"></i>12
                    Comments</span
                  >
                </div>
                <div class="col-2 align-items-end text-end">
                  <div class="button text-center">READ MORE</div>
                </div>
              </div>
            </article>
            <article class="margin border-bottom py-4">
              <img :src="require('@/assets/images/blog-58a.jpg')" alt="" />
              <div class="info d-flex">
                <div class="date d-flex flex-column mt-3">
                  <span class="day fw-bold text-center">12</span>
                  <span class="month fw-bold text-white text-center">JAN</span>
                </div>
                <div class="title mx-3 mt-3">
                  <h3>Top Camper Trailer Towing Tips</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nesciunt corporis adipisci repellat maiores eum cupiditate
                    aut molestiae modi, nulla explicabo quo fugit doloremque
                    voluptatem quasi deleniti. Adipisci eveniet omnis harum,
                    nulla explicabo quo fugit doloremque voluptatem quasi
                    deleniti! Proin rhoncus consequat nisl, eu ornare mauris
                    tincidunt vitae. [...]
                  </p>
                </div>
              </div>
              <div class="row justify-content-between readable">
                <div class="col-6">
                  <span
                    ><i class="fa-regular fa-user mx-1"></i>By John Doe</span
                  >
                  <span class="mx-3"
                    ><i class="fa-regular fa-folder mx-1"></i>Travel,
                    Lifestyle</span
                  >
                  <span
                    ><i class="fa-regular fa-comments mx-1"></i>12
                    Comments</span
                  >
                </div>
                <div class="col-2 align-items-end text-end">
                  <div class="button text-center">READ MORE</div>
                </div>
              </div>
            </article>
            <article class="margin border-bottom py-4">
              <div class="row p-2">
                <div class="col-4 p-0">
                  <img :src="require('@/assets/images/blog-13.jpg')" alt="" />
                </div>
                <div class="col-4 p-0">
                  <img :src="require('@/assets/images/blog-16.jpg')" alt="" />
                </div>
                <div class="col-4 p-0">
                  <img :src="require('@/assets/images/blog-20.jpg')" alt="" />
                </div>
                <div class="col-4 p-0">
                  <img :src="require('@/assets/images/blog-23.jpg')" alt="" />
                </div>
                <div class="col-4 p-0">
                  <img :src="require('@/assets/images/blog-29.jpg')" alt="" />
                </div>
                <div class="col-4 p-0">
                  <img :src="require('@/assets/images/blog-40.jpg')" alt="" />
                </div>
              </div>
              <div class="info d-flex">
                <div class="date d-flex flex-column mt-3">
                  <span class="day fw-bold text-center">8</span>
                  <span class="month fw-bold text-white text-center">JAN</span>
                </div>
                <div class="title mx-3 mt-3">
                  <h3>10 Best Travel Tips After 5 Years Traveling The World</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nesciunt corporis adipisci repellat maiores eum cupiditate
                    aut molestiae modi, nulla explicabo quo fugit doloremque
                    voluptatem quasi deleniti. Adipisci eveniet omnis harum,
                    nulla explicabo quo fugit doloremque voluptatem quasi
                    deleniti! Proin rhoncus consequat nisl, eu ornare mauris
                    tincidunt vitae. [...]
                  </p>
                </div>
              </div>
              <div class="row justify-content-between readable">
                <div class="col-6">
                  <span
                    ><i class="fa-regular fa-user mx-1"></i>By John Doe</span
                  >
                  <span class="mx-3"
                    ><i class="fa-regular fa-folder mx-1"></i>Lifestyle,
                    Travel</span
                  >
                  <span
                    ><i class="fa-regular fa-comments mx-1"></i>12
                    Comments</span
                  >
                </div>
                <div class="col-2 align-items-end text-end">
                  <div class="button text-center">READ MORE</div>
                </div>
              </div>
            </article>
            <div class="row justify-content-between mt-5">
              <div class="col text-end align-items-end p-0 m-0">
                <nav class="text-end">
                  <ul class="pagination text-end">
                    <li class="page-item p-0 m-0">
                      <a class="page-link" href="#" aria-label="Previous">
                        <span aria-hidden="true">
                          <i class="fa-solid fa-angle-left"></i>
                        </span>
                        <span class="sr-only">Previous</span>
                      </a>
                    </li>
                    <li class="page-item p-0 m-0">
                      <a class="page-link" href="#">1</a>
                    </li>
                    <li class="page-item p-0 m-0">
                      <a class="page-link" href="#">2</a>
                    </li>
                    <li class="page-item p-0 m-0">
                      <a class="page-link" href="#">3</a>
                    </li>
                    <li class="page-item p-0 m-0">
                      <a class="page-link" href="#" aria-label="Next">
                        <span aria-hidden="true">
                          <i class="fa-solid fa-angle-right"></i>
                        </span>
                        <span class="sr-only">Next</span>
                      </a>
                    </li>
                  </ul>
                </nav>
              </div>
            </div>
          </div>
          <div class="col-3">
            <h6 class="fw-bold mt-4 py-3">LATEST FROM TWITTER</h6>
            <div class="d-flex">
              <span><i class="fa-brands fa-twitter fa-lg mx-1"></i> </span>
              <p class="p-0 m-0">
                If you have any suggestions for the next updates, let us know.
              </p>
            </div>
            <span class="bottomdate">01:05 PM Sep 18th</span>

            <div class="d-flex mt-3">
              <span><i class="fa-brands fa-twitter fa-lg mx-1"></i> </span>
              <p class="p-0 m-0">
                We have just updated Porto Admin. Check the changelog for more
                information.
              </p>
            </div>
            <span class="bottomdate">01:04 PM Sep 18th</span>
            <h6 class="fw-bold mt-4 py-3">PHOTOS FROM INSTAGRAM</h6>
            <div class="row p-2">
              <div class="col-4 m-0 p-0">
                <img
                  :src="
                    require('@/assets/images/29739607_2020680068220520_4509928046932787200_n.jpg')
                  "
                  alt=""
                  class="pointer"
                />
              </div>
              <div class="col-4 m-0 p-0">
                <img
                  :src="
                    require('@/assets/images/30087804_253872848488989_8792603541668626432_n.jpg')
                  "
                  alt=""
                  class="pointer"
                />
              </div>
              <div class="col-4 m-0 p-0">
                <img
                  :src="
                    require('@/assets/images/29415620_196477127626244_3250318472361541632_n.jpg')
                  "
                  alt=""
                  class="pointer"
                />
              </div>
              <div class="col-4 m-0 p-0">
                <img
                  :src="
                    require('@/assets/images/30078414_1274410412703843_8290935809419247616_n.jpg')
                  "
                  alt=""
                  class="pointer"
                />
              </div>
              <div class="col-4 m-0 p-0">
                <img
                  :src="
                    require('@/assets/images/30077195_2066750973610181_3733150062893596672_n.jpg')
                  "
                  alt=""
                  class="pointer"
                />
              </div>
              <div class="col-4 m-0 p-0">
                <img
                  :src="
                    require('@/assets/images/29415304_166583630713703_1032667922171953152_n.jpg')
                  "
                  alt=""
                  class="pointer"
                />
              </div>
            </div>
            <h6 class="fw-bold mt-4 py-3">TAGS</h6>
            <div class="row justify-content-between px-2">
              <div
                class="
                  col-2
                  bg-dark
                  text-white
                  fw-bold
                  text-center
                  pointer
                  px-1
                "
              >
                DESIGN
              </div>
              <div
                class="
                  col-2
                  bg-dark
                  text-white
                  fw-bold
                  text-center
                  pointer
                  px-1
                "
              >
                BRANDS
              </div>
              <div
                class="
                  col-2
                  bg-dark
                  text-white
                  fw-bold
                  text-center
                  pointer
                  px-1
                "
              >
                VIDEO
              </div>
              <div
                class="
                  col-2
                  bg-dark
                  text-white
                  fw-bold
                  text-center
                  pointer
                  px-1
                "
              >
                BUSINESS
              </div>
              <div
                class="
                  col-2
                  bg-dark
                  text-white
                  fw-bold
                  text-center
                  pointer
                  px-1
                "
              >
                TRAVEL
              </div>
            </div>
            <h6 class="fw-bold mt-4 py-3">FIND US ON FACEBOOK</h6>
            <p class="okler pointer p-2">Okler Themes</p>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "src/assets/sass/style.scss";

.col-4 img {
  width: 100%;
}

#post {
  padding-top: 40px;
  padding-bottom: 40px;
}

.posts {
  cursor: pointer;
}

.pointer {
  cursor: pointer;
}
#grey {
  background-color: #f7f7f7;
  padding-top: 40px;
  padding-bottom: 40px;
}

.post-image img {
  width: 50px;
}

.post-description span {
  color: #888888;
}

.date {
  font-size: 12px;
}

h5 {
  font-size: 14px;
}

.image {
  min-width: 110px;
}

p {
  color: #888888;
}

#green {
  background-color: $primary-color;
  padding-top: 40px;
  padding-bottom: 40px;
}

.btn-black {
  background-color: black;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-right: 25px;
  padding-left: 25px;
}

#blog {
  padding-top: 40px;
  padding-bottom: 80px;
}

article {
  cursor: pointer;
}

article img {
  width: 100%;
}

.day {
  background-color: #f7f7f7;
  padding: 10px;
  width: 40px;
}

.month {
  background-color: black;
  padding: 5px;
  width: 40px;
  font-size: 9px;
}

.col-6 span {
  font-size: 13px;
  cursor: pointer;
  color: $primary-color;

  .fa-regular {
    color: #888888;
  }
}

.button {
  font-size: 11px;
  color: #777777;
  border: 1px solid #e2e2e2;
  border-radius: 5px;
  padding: 5px;
  cursor: pointer;
}

.margin {
  margin-top: 40px;
}

.readable {
  padding-left: 50px;
}

.relative {
  position: relative;
  cursor: pointer;
}

.bright {
  filter: brightness(0.7);
}

.categories {
  background-color: $primary-color;
  padding: 2px 5px;
  border-radius: 2px;
  position: absolute;
  left: 25px;
  bottom: 70px;
}

#light {
  filter: brightness(1.0);
}

.relative:hover {


  img {
    filter: brightness(0.4);
  }
  
  .categories {
    bottom: 120px;
  }

  .bottom-categories {
    bottom: 100px;
  }

  .minicategories {
    bottom: 340px;
  }

  .toptitle {
    bottom: 60px;
  }

  .minititle {
    bottom: 280px;
  }

  .sottotitolo {
    bottom: 10px;
    display: block;
  }

  .sidetitle {
    bottom: 235px;
    display: block;
  }
}

.sottotitolo {
  font-size: 12px;
  color: lightgrey;
  position: absolute;
  left: 25px;
  padding-right: 5px;
  bottom: 50px;
  display: none;
}

.sidetitle {
  bottom: 10px;
  position: absolute;
  left: 25px;
  display: none;
  font-size: 12px;
  color: lightgrey;
}

.bottom-categories {
  background-color: $primary-color;
  padding: 2px 5px;
  border-radius: 2px;
  position: absolute;
  left: 25px;
  bottom: 50px;
}

.subtitle {
  font-size: 10px;
}

.toptitle {
  font-weight: bold;
  font-size: 18px;
  color: white;
  position: absolute;
  left: 10px;
  bottom: 10px;
}

.minititle {
  font-weight: bold;
  font-size: 18px;
  color: white;
  position: absolute;
  left: 10px;
  bottom: 240px;
}

.minicategories {
  background-color: $primary-color;
  padding: 2px 5px;
  border-radius: 2px;
  position: absolute;
  left: 25px;
  bottom: 300px;
}

.bottomdate {
  color: $primary-color;
  font-size: 13px;
  margin-left: 30px;
}

.row .col-2 {
  font-size: 10px;
  border-radius: 50px;
}

.okler {
  color: $primary-color;
  border-left: 5px solid #e2e2e2;
}

.page-item .page-link {
  color: $primary-color;
}

.frame:hover {
  filter: opacity(0.9);
}
</style>