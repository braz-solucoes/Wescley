<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/um.png')">
      </parallax>
      <div class="content-center">
        <div class="container">
          <transition appear>
            <h1 class="title1">Vote 70</h1>
          </transition>
          <transition appear>
            <div class="text-center">
              <img src="img/dois.png" alt="" style="width: 550px" />
              <!-- <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-facebook-square"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#pablo" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-google-plus"></i>
            </a> -->
            </div>
          </transition>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row" style="opacity: 0.8">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <transition appear="">
              <h2 class="title">Com o povo, para o povo!</h2>
            </transition>
          </div>
        </div>
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="background-image: url('img/cortada2.jpg')">
                <!-- First image on the left side -->
                <!-- <p class="blockquote blockquote-primary">
                  "Over the span of the satellite record, Arctic sea ice has
                  been declining significantly, while sea ice in the
                  Antarctichas increased very slightly"
                  <br />
                  <br />
                  <small>-NOAA</small>
                </p> -->
              </div>
              <!-- Second image on the left side of the article -->
              <!-- <div
                class="image-container"
                style="background-image: url('img/cortada1.jpg')"></div> -->
            </div>
            <div class="col-md-5">
              <!-- First image on the right side, above the article -->
              <transition appear>
                <div
                  class="image-container image-right"
                  style="background-image: url('img/cortada1.jpg')"></div>
              </transition>
              <!-- <h3>
                So what does the new record for the lowest level of winter ice
                actually mean
              </h3>
              <p>
                The Arctic Ocean freezes every winter and much of the sea-ice
                then thaws every summer, and that process will continue whatever
                happens with climate change. Even if the Arctic continues to be
                one of the fastest-warming regions of the world, it will always
                be plunged into bitterly cold polar dark every winter. And
                year-by-year, for all kinds of natural reasons, there’s huge
                variety of the state of the ice.
              </p>
              <p>
                For a start, it does not automatically follow that a record
                amount of ice will melt this summer. More important for
                determining the size of the annual thaw is the state of the
                weather as the midnight sun approaches and temperatures rise.
                But over the more than 30 years of satellite records, scientists
                have observed a clear pattern of decline, decade-by-decade.
              </p>
              <p>
                The Arctic Ocean freezes every winter and much of the sea-ice
                then thaws every summer, and that process will continue whatever
                happens with climate change. Even if the Arctic continues to be
                one of the fastest-warming regions of the world, it will always
                be plunged into bitterly cold polar dark every winter. And
                year-by-year, for all kinds of natural reasons, there’s huge
                variety of the state of the ice.
              </p> -->
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- <card class="card-image"></card> -->
    <tabs-section></tabs-section>
    <carousel-section></carousel-section>
    <transition appear>
      <div
        class="section1 section-team text-center"
        style="background-image: url('img/agorabanner.png')">
        <div class="container">
          <transition appear="">
            <h2 class="title">Nossos projetos</h2>
          </transition>
          <div class="team">
            <div class="row">
              <div class="col-md-4">
                <div class="team-player" style="background-color: #f15a01">
                  <img
                    src="img/agoraredondo.png"
                    alt="Thumbnail Image"
                    class="rounded-circle img-fluid img-raised"
                    style="margin-top: 1cm" />
                  <h4 class="title1">Familia</h4>
                  <p class="category text-primary">Model</p>
                  <p class="description">
                    You can write here details about one of your team members.
                    You can give more details about what they do. Feel free to
                    add some <a href="#">links</a> for people to be able to
                    follow them outside the site.
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-twitter"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-instagram"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-facebook-square"></i
                  ></a>
                </div>
              </div>

              <div class="col-md-4">
                <div class="team-player" style="background-color: #f15a01">
                  <img
                    src="img/agoraredondo.png"
                    alt="Thumbnail Image"
                    class="rounded-circle img-fluid img-raised"
                    style="margin-top: 1cm" />

                  <h4 class="title1">Educação</h4>
                  <p class="category text-primary">Designer</p>
                  <p class="description">
                    You can write here details about one of your team members.
                    You can give more details about what they do. Feel free to
                    add some <a href="#">links</a> for people to be able to
                    follow them outside the site.
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-twitter"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-linkedin"></i
                  ></a>
                </div>
              </div>
              <div class="col-md-4">
                <div
                  class="team-player animacao"
                  style="background-color: #f15a01">
                  <img
                    src="img/agoraquadrado.png"
                    alt="Thumbnail Image"
                    class="rounded img-fluid img-raised"
                    style="margin-top: 1cm" />
                  <h4 class="title1">Saúde</h4>
                  <p class="category text-primary">Fashion</p>
                  <p class="description">
                    You can write here details about one of your team members.
                    You can give more details about what they do. Feel free to
                    add some <a href="#">links</a> for people to be able to
                    follow them outside the site.
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-google-plus"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-youtube"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-twitter"></i
                  ></a>
                </div>
              </div>
            </div>
          </div>
          <div class="team">
            <div class="row">
              <div class="col-md-4">
                <div
                  class="team-player animacao"
                  style="background-color: #f15a01">
                  <img
                    src="img/agoraredondo.png"
                    alt="Thumbnail Image"
                    class="rounded-circle img-fluid img-raised"
                    style="margin-top: 1cm" />
                  <h4 class="title1">Familia</h4>
                  <p class="category text-primary">Model</p>
                  <p class="description">
                    You can write here details about one of your team members.
                    You can give more details about what they do. Feel free to
                    add some <a href="#">links</a> for people to be able to
                    follow them outside the site.
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-twitter"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-instagram"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-facebook-square"></i
                  ></a>
                </div>
              </div>
              <div class="col-md-4">
                <div
                  class="team-player animacao"
                  style="background-color: #f15a01">
                  <img
                    src="img/agoraredondo.png"
                    alt="Thumbnail Image"
                    class="rounded-circle img-fluid img-raised"
                    style="margin-top: 1cm" />
                  <h4 class="title1">Educação</h4>
                  <p class="category text-primary">Designer</p>
                  <p class="description">
                    You can write here details about one of your team members.
                    You can give more details about what they do. Feel free to
                    add some <a href="#">links</a> for people to be able to
                    follow them outside the site.
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-twitter"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-linkedin"></i
                  ></a>
                </div>
              </div>
              <div class="col-md-4">
                <div
                  class="team-player animacao"
                  style="background-color: #f15a01">
                  <img
                    src="img/agoraquadrado.png"
                    alt="Thumbnail Image"
                    class="rounded img-fluid img-raised"
                    style="margin-top: 1cm" />
                  <h4 class="title1">Saúde</h4>
                  <p class="category text-primary">Fashion</p>
                  <p class="description">
                    You can write here details about one of your team members.
                    You can give more details about what they do. Feel free to
                    add some <a href="#">links</a> for people to be able to
                    follow them outside the site.
                  </p>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-google-plus"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-youtube"></i
                  ></a>
                  <a href="#pablo" class="btn btn-primary btn-icon btn-round"
                    ><i class="fab fa-twitter"></i
                  ></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </transition>
    <div class="section section-contact-us text-center">
      <div class="container">
        <h2 class="title">Want to work with us?</h2>
        <p class="description">Your project is very important to us.</p>
        <div class="row">
          <div
            class="col-lg-6 text-center ml-auto mr-auto col-md-8"
            style="background-color: #ffff">
            <fg-input
              class="input-lg"
              placeholder="Primeiro nome"
              v-model="form.firstName"
              addon-left-icon="now-ui-icons users_circle-08">
            </fg-input>
            <fg-input
              class="input-lg"
              placeholder="Email"
              v-model="form.email"
              addon-left-icon="now-ui-icons ui-1_email-85">
            </fg-input>
            <div class="textarea-container">
              <textarea
                class="form-control"
                name="name"
                rows="4"
                cols="80"
                v-model="form.message"
                placeholder="Type a message..."></textarea>
            </div>
            <div class="send-button">
              <n-button type="primary" round block size="lg"
                >Envie mensagem</n-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Button, FormGroupInput } from '@/components';
import CarouselSection from './components/CarouselSection';
import TabsSection from './components/Tabs';
export default {
  name: 'landing',
  bodyClass: 'landing-page',
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput,
    CarouselSection,
    TabsSection,
    // Card,
  },
  data() {
    return {
      form: {
        firstName: '',
        email: '',
        message: '',
      },
    };
  },
};
</script>

<style scoped>
.v-enter-active,
.v-leave-active {
  transition: opacity 2s;
}
.v-enter,
.v-leave-to {
  opacity: 0;
}
</style>
