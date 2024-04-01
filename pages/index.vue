<script setup lang="ts">
import type { QueryBuilderParams } from "@nuxt/content/dist/runtime/types";
const query: QueryBuilderParams = {
  path: "/blog",
  limit: 3,
  sort: [{ date: -1 }],
};
</script>

<template>
  <section
    data-aos="fade-right"
    data-aos-duration="2000"
    data-bs-version="5.1"
    class="start article4 cid-u89VvpUPLG"
    id="article04-22"
  >
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-12 col-md-12 col-lg-5 image-wrapper">
          <img
            class="w-100 h-100"
            src="/images/lilitha_mdlalana.jpg"
            alt="Lilitha Mdlalana"
          />
        </div>
        <div class="col-12 col-md-12 col-lg">
          <div class="text-wrapper align-left">
            <h1 class="mbr-section-title mbr-fonts-style mb-4 display-2">
              I'm<strong> Lilitha Mdlalana</strong>.
            </h1>
            <p class="mbr-text mbr-fonts-style mb-4 display-7">
              👋 Hey there! I'm <em>Lilitha</em>, a
              <strong>software developer </strong>with a passion for building
              user interfaces. Welcome to my little corner of the web where I
              share notes,code snippets and resources on topics that interest
              me.
            </p>
            <div class="mbr-section-btn mt-3">
              <a class="btn btn-lg btn-black display-7" href="https://mobiri.se"
                >Contact me</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section
    data-bs-version="5.1"
    class="article12 cid-u89XTo4Ffx"
    id="about"
    data-aos="fade-down"
    data-aos-duration="2000"
  >
    <div id="about" class="container">
      <div class="row justify-content-center">
        <div class="col-md-12 col-lg-10">
          <h3 class="mbr-section-title mbr-fonts-style mb-4 mt-0 display-2">
            A little<strong> about me...</strong>
          </h3>

          <p class="mbr-text mbr-fonts-style display-7">
            I started software development&nbsp; in 2019 back in high school as
            a hobby, after learning about the all kinds of cool things you could
            build with computer programming...<br />
            <br />Video games, social media networks, the software that we use
            to make payments, all have some programming language in them(most
            likely <strong>Java</strong> 😁). And it all started with a
            obsession for <strong>sci-fi movies</strong> where I fell in love
            with robotics, arduinos and seeing one's and zero's going up a
            screen in the <strong>Matrix</strong>. And they wanted me to be a
            lawyer, a doctor or something else 😔...<br />
            <br />When I'm not programming, I'm playing video games, watching a
            sci-fi movie, playing/watching football&nbsp;⚽ or keeping up to
            date with what Elon is up to (side note: I'm a fan&nbsp;🤓 ).
          </p>
        </div>
      </div>
    </div>
  </section>

  <section
    data-bs-version="5.1"
    class="features16 cid-u89ZTLDGvh"
    id="skills"
    data-aos="zoom-in"
    data-aos-duration="2000"
  >
    <div class="container">
      <div class="row justify-content-center mb-5">
        <div class="col-12 content-head">
          <h4
            class="mbr-section-title mbr-fonts-style align-center mb-0 display-2"
          >
            <strong>Tech I like and use...</strong>
          </h4>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="item features-without-image col-12 col-lg-4 active">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/javascript-svgrepo-com.svg"
                    data-slide-to="0"
                    data-bs-slide-to="0"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>JavaScript</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The popular kid on the block.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/react-javascript-js-framework-facebook-svgrepo-com.svg"
                    data-slide-to="1"
                    data-bs-slide-to="1"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>React</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The smooth operator of the frontend world.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/vue-svgrepo-com.svg"
                    data-slide-to="2"
                    data-bs-slide-to="2"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>Vue</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The zen master of front-end frameworks.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/python-svgrepo-com.svg"
                    data-slide-to="3"
                    data-bs-slide-to="3"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>Python</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The smooth-talker at the coding-cocktail party.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/django-svgrepo-com.svg"
                    alt="Django"
                    data-slide-to="4"
                    data-bs-slide-to="4"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>Django</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The superhero of web frameworks.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/java-svgrepo-com.svg"
                    alt="Java"
                    data-slide-to="5"
                    data-bs-slide-to="5"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>Java</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The timeless titan of the coding realm.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/git-svgrepo-com.svg"
                    alt="Java"
                    data-slide-to="6"
                    data-bs-slide-to="6"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>Git</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                The guardian angel of your codebase.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
        <div class="item features-without-image col-12 col-lg-4">
          <div class="item-wrapper">
            <div class="card-box">
              <div class="img-box">
                <div class="image-wrapper mb-3">
                  <img
                    src="assets/images/vscode-svgrepo-com.svg"
                    alt="Java"
                    data-slide-to="7"
                    data-bs-slide-to="8"
                  />
                </div>
              </div>
              <h4 class="card-title mbr-fonts-style mb-0 display-7">
                <strong>Visual Studio Code</strong>
              </h4>
              <h5 class="card-text mbr-fonts-style mt-3 display-7">
                Everyone's trusty sidekick for coding adventures.
              </h5>
              <div class="link-wrap"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section
    data-aos="fade-down"
    data-aos-duration="2000"
    data-bs-version="5.1"
    class="gallery1 mbr-gallery cid-u89YfZdymR"
    id="projects"
  >
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 content-head">
          <div class="mb-5">
            <h3
              class="mbr-section-title mbr-fonts-style align-center m-0 display-2"
            >
              <strong>Projects.</strong>
            </h3>
            <h4
              class="mbr-section-subtitle mbr-fonts-style align-center mb-0 mt-4 display-7"
            >
              Some stuff I've built...
            </h4>
          </div>
        </div>
      </div>

      <div class="row mbr-gallery">
        <div class="col-12 col-md-6 col-lg-3 item gallery-image">
          <div
            class="item-wrapper mb-3"
            data-toggle="modal"
            data-bs-toggle="modal"
            data-target="#u8xLDogWj3-modal"
            data-bs-target="#u8xLDogWj3-modal"
          >
            <img
              class="w-100"
              src="/images/gallery01.jpg"
              data-slide-to="0"
              data-bs-slide-to="0"
              data-target="#lb-u8xLDogWj3"
              data-bs-target="#lb-u8xLDogWj3"
            />
            <div class="icon-wrapper">
              <span
                class="mobi-mbri mobi-mbri-search mbr-iconfont mbr-iconfont-btn"
              ></span>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 item gallery-image">
          <div
            class="item-wrapper mb-3"
            data-toggle="modal"
            data-bs-toggle="modal"
            data-target="#u8xLDogWj3-modal"
            data-bs-target="#u8xLDogWj3-modal"
          >
            <img
              class="w-100"
              src="/images/gallery02.jpg"
              data-slide-to="1"
              data-bs-slide-to="1"
              data-target="#lb-u8xLDogWj3"
              data-bs-target="#lb-u8xLDogWj3"
            />
            <div class="icon-wrapper">
              <span
                class="mobi-mbri mobi-mbri-search mbr-iconfont mbr-iconfont-btn"
              ></span>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 item gallery-image">
          <div
            class="item-wrapper mb-3"
            data-toggle="modal"
            data-bs-toggle="modal"
            data-target="#u8xLDogWj3-modal"
            data-bs-target="#u8xLDogWj3-modal"
          >
            <img
              class="w-100"
              src="/images/gallery03.jpg"
              data-slide-to="2"
              data-bs-slide-to="2"
              data-target="#lb-u8xLDogWj3"
              data-bs-target="#lb-u8xLDogWj3"
            />
            <div class="icon-wrapper">
              <span
                class="mobi-mbri mobi-mbri-search mbr-iconfont mbr-iconfont-btn"
              ></span>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 item gallery-image">
          <div
            class="item-wrapper mb-3"
            data-toggle="modal"
            data-bs-toggle="modal"
            data-target="#u8xLDogWj3-modal"
            data-bs-target="#u8xLDogWj3-modal"
          >
            <img
              class="w-100"
              src="/images/gallery04.jpg"
              data-slide-to="3"
              data-bs-slide-to="3"
              data-target="#lb-u8xLDogWj3"
              data-bs-target="#lb-u8xLDogWj3"
            />
            <div class="icon-wrapper">
              <span
                class="mobi-mbri mobi-mbri-search mbr-iconfont mbr-iconfont-btn"
              ></span>
            </div>
          </div>
        </div>
      </div>

      <div
        class="modal mbr-slider"
        tabindex="-1"
        role="dialog"
        aria-hidden="true"
        id="u8xLDogWj3-modal"
      >
        <div class="modal-dialog" role="document">
          <div class="modal-content">
            <div class="modal-body">
              <div
                class="carousel slide"
                data-pause="false"
                data-bs-pause="false"
                id="lb-u8xLDogWj3"
                data-interval="5000"
                data-bs-interval="5000"
              >
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img class="d-block w-100" src="/images/gallery01.jpg" />
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="/images/gallery02.jpg" />
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="/images/gallery03.jpg" />
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="/images/gallery04.jpg" />
                  </div>
                </div>
                <ol class="carousel-indicators">
                  <li
                    data-slide-to="0"
                    data-bs-slide-to="0"
                    class="active"
                    data-target="#lb-u8xLDogWj3"
                    data-bs-target="#lb-u8xLDogWj3"
                  ></li>
                  <li
                    data-slide-to="1"
                    data-bs-slide-to="1"
                    data-target="#lb-u8xLDogWj3"
                    data-bs-target="#lb-u8xLDogWj3"
                  ></li>
                  <li
                    data-slide-to="2"
                    data-bs-slide-to="2"
                    data-target="#lb-u8xLDogWj3"
                    data-bs-target="#lb-u8xLDogWj3"
                  ></li>
                  <li
                    data-slide-to="3"
                    data-bs-slide-to="3"
                    data-target="#lb-u8xLDogWj3"
                    data-bs-target="#lb-u8xLDogWj3"
                  ></li>
                </ol>
                <a
                  role="button"
                  href=""
                  class="close"
                  data-dismiss="modal"
                  data-bs-dismiss="modal"
                  aria-label="Close"
                >
                </a>
                <a
                  class="carousel-control-prev carousel-control"
                  role="button"
                  data-slide="prev"
                  data-bs-slide="prev"
                  href="#lb-u8xLDogWj3"
                >
                  <span
                    class="mobi-mbri mobi-mbri-arrow-prev"
                    aria-hidden="true"
                  ></span>
                  <span class="sr-only visually-hidden">Previous</span>
                </a>
                <a
                  class="carousel-control-next carousel-control"
                  role="button"
                  data-slide="next"
                  data-bs-slide="next"
                  href="#lb-u8xLDogWj3"
                >
                  <span
                    class="mobi-mbri mobi-mbri-arrow-next"
                    aria-hidden="true"
                  ></span>
                  <span class="sr-only visually-hidden">Next</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section
    data-bs-version="5.1"
    class="news08 cid-u8fImvMfJs"
    id="thoughts"
    data-aos="fade-down"
    data-aos-duration="2000"
  >
    <div class="container">
      <div class="row justify-content-center mb-5">
        <div class="col-12 content-head">
          <div class="mbr-section-head">
            <h4
              class="mbr-section-title mbr-fonts-style align-center mb-0 display-2"
            >
              <strong>Some thoughts...</strong>
            </h4>
          </div>
        </div>
      </div>
      <ContentList :query="query" path="/blog" v-slot="{ list }">
        <div class="row">
          <SharedArticleCard
            v-for="post in list"
            :key="post._path"
            :articleTitle="post.title"
            :articleGenre="post.tag"
            :articleImageUrl="post.thumbnail"
            :articleUrl="post.slug"
          />
        </div>
      </ContentList>
    </div>
  </section>

  <SectionContact />
</template>
