<template>
  <main>
    <section id="grey">
      <div class="container">
        <div class="row h-100">
          <div class="col-4 my-3">
            <img :src="require('@/assets/images/blog-46.jpg')" alt="" />
          </div>
          <div class="col-4 my-3">
            <img :src="require('@/assets/images/blog-47.jpg')" alt="" />
          </div>
          <div class="col-4 my-3">
            <img :src="require('@/assets/images/blog-48.jpg')" alt="" />
          </div>
          <div class="col-4 my-3">
            <img :src="require('@/assets/images/blog-49.jpg')" alt="" />
          </div>
          <div class="col-4 my-3">
            <img :src="require('@/assets/images/blog-50.jpg')" alt="" />
          </div>
          <div class="col-4 my-3">
            <img :src="require('@/assets/images/blog-51.jpg')" alt="" />
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
                <img :src="require('@/assets/images/blog-66.jpg')" alt="" />
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
          <div class="col-4">
            <h5 class="fw-bold mb-3">FEATURED POSTS</h5>
            <img :src="require('@/assets/images/blog-66.jpg')" alt="" />
            <h5 class="fw-bold mt-3">FEATURED AUTHOR</h5>
            <div class="posts d-flex my-3">
              <div class="image">
                <img :src="require('@/assets/images/avatar.jpg')" alt="" />
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
          <div class="">
            <i class="fa-solid fa-angle-left"></i>
          </div>
          <div class="col">
            <span class="fw-bold text-white btn-black">GADGETS</span>
          </div>
          <div class="col">
            <span class="fw-bold text-white btn-black">PHOTOGRAPHY</span>
          </div>
          <div class="col">
            <span class="fw-bold text-white btn-black">LIFESTYLE</span>
          </div>
          <div class="col">
            <span class="fw-bold text-white btn-black">FASHION</span>
          </div>
          <div class="col">
            <span class="fw-bold text-white btn-black">RECIPES</span>
          </div>
          <div class="col">
            <span class="fw-bold text-white btn-black">TRAVEL</span>
          </div>
          <div class="">
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
              <div class="row justify-content-between">
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
              <div class="row justify-content-between">
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
              <div class="row justify-content-between">
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
              <div class="row">
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
              <div class="row justify-content-between">
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
          </div>
          <div class="col-3"></div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss">
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
  padding-bottom: 40px;
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

  & .fa-regular {
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
</style>