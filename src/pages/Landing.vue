<template>
  <div>
    <div class="page-header page-header">
      <parallax
        class="page-header-image"
        style="background-image: url('img/bannerfinal.png')">
      </parallax>
      <div class="content-center">
        <div class="container">
          <transition appear>
            <div class="text-right">
              <img src="img/dois.png" alt="" style="width: 700px" />
            </div>
          </transition>
        </div>
      </div>
      <div class="content-center">
        <div class="container">
          <transition appear>
            <div class="text-left">
              <img
                src="img/avantesemfundo.png"
                alt=""
                style="width: 230px; margin: 25px 0px 0px 50px" />
            </div>
          </transition>
        </div>
        <div class="content-center">
          <div class="container">
            <transition appear>
              <div class="text-left">
                <img
                  src="img/compromissosemfundo.png"
                  alt=""
                  style="width: 700px; margin: 0px 0px 500px -300px" />
              </div>
            </transition>
          </div>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row" style="opacity: 0.85">
          brazsolucoes.
          <div class="col-md-8 ml-auto mr-auto text-center">
            <transition appear="">
              <h2 class="title" id="povo" style="text-transform: uppercase">
                O povo pediu, a mudança chegou!
              </h2>
            </transition>
          </div>
        </div>
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="background-image: url('img/cortada2.jpg')"></div>
              <h1
                style="
                  margin-top: 3cm;
                  color: #ffff;
                  font-weight: bold;
                  text-align: center;
                  background-color: #f15a01;
                  padding: 5px;
                  border-radius: 10px;
                  font-size: 500%;
                  text-transform: uppercase;
                ">
                DiáloGo e ação!
              </h1>
              <!-- Second image on the left side of the article -->
              <!-- <div
                class="image-container"
                style="background-image: url('img/cortada1.jpg')"></div> -->
            </div>
            <div class="col-md-6">
              <!-- First image on the right side, above the article -->
              <transition appear>
                <div
                  class="image-container image-right"
                  style="background-image: url('img/cortada1.jpg')"></div>
              </transition>

              <p
                class="blockquote-sucess blockquote-success"
                style="
                  background-color: #fff;
                  padding: 15px;
                  border-radius: 10px;
                  color: #f15a01;
                  font-weight: bold;
                ">
                The Arctic Ocean freezes every winter and much of the sea-ice
                then thaws every summer, and that process will continue whatever
                happens with climate change. Even if the Arctic continues to be
                one of the fastest-warming regions of the world, it will always
                be plunged into bitterly cold polar dark every winter. And
                year-by-year, for all kinds of natural reasons, there’s huge
                variety of the state of the ice.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-10 ml-auto col-xl-5 mr-auto"></div>
    </div>
    <div class="section">
      <div class="">
        <div class="row">
          <div class="col-md-6">
            <carousel-section></carousel-section>
          </div>
          <div class="col-md-5">
            <!-- First image on the left side -->
            <p
              class="blockquote-sucess blockquote-success"
              style="
                margin-top: 3cm;
                background-color: #fff;
                padding: 15px;
                border-radius: 10px;
                color: #f15a01;
                font-weight: bold;
              ">
              "Over the span of the satellite record, Arctic sea ice has been
              declining significantly, while sea ice in the Antarctichas
              incre10pxased very slightly"
              <br />
              <br />
              <mid>-Fulano de tal</mid>
            </p>
            <card style="border-radius: 10px">
              <tabs
                centered
                type="neutral"
                tab-nav-wrapper-classes="card-header"
                data-background-color="orange">
                <tab-pane>
                  <template slot="label">
                    <i class="now-ui-icons objects_umbrella-13"></i> Vote
                  </template>
                  <p>
                    I think that’s a responsibility that I have, to push
                    possibilities, to show people, this is the level that things
                    could be at. So when you get something that has the name
                    Kanye West on it, it’s supposed to be pushing the furthest
                    possibilities. I will be the leader of a company that ends
                    up being worth billions of dollars, because I got the
                    answers. I understand culture. I am the nucleus.
                  </p>
                </tab-pane>
                <tab-pane>
                  <template slot="label">
                    <i class="now-ui-icons shopping_cart-simple"></i> home
                  </template>
                  <p>
                    I will be the leader of a company that ends up being worth
                    billions of dollars, because I got the answers. I understand
                    culture. I am the nucleus. I think that’s a responsibility
                    that I have, to push possibilities, to show people, this is
                    the level that things could be at. I think that’s a
                    responsibility that I have, to push possibilities, to show
                    people, this is the level that things could be at.
                  </p>
                </tab-pane>
                <tab-pane>
                  <template slot="label">
                    <i class="now-ui-icons shopping_shop"></i> coligação
                  </template>
                  <p>
                    I think that’s a responsibility that I have, to push
                    possibilities, to show people, this is the level that things
                    could be at. So when you get something that has the name
                    Kanye West on it, it’s supposed to be pushing the furthest
                    possibilities. I will be the leader of a company that ends
                    up being worth billions of dollars, because I got the
                    answers. I understand culture. I am the nucleus.
                  </p>
                </tab-pane>
                <tab-pane>
                  <template slot="label">
                    <i class="now-ui-icons ui-2_settings-90"></i> Outros
                  </template>
                  <img
                    src="img/avantesemfundo.png"
                    style="display: block; margin: auto; margin-bottom: -1cm" />
                </tab-pane>
              </tabs>
            </card>
            <!-- <p class="blockquote blockquote-primary" style="margin-top: 2cm">
              "Over the span of the satellite record, Arctic sea ice has been
              declining significantly, while sea ice in the Antarctichas
              increased very slightly"
              <br />
              <br />
              <small>-NOAA</small>
            </p> -->
          </div>
        </div>
      </div>
    </div>
    <transition appear>
      <div
        class="section1 section-team text-center"
        style="background-image: url('img/agorabanner.png')">
        <div class="container">
          <transition appear="">
            <h2 class="title" id="projetos">Nossos projetos</h2>
          </transition>
          <div class="team">
            <div class="row">
              <div class="col-md-4" style="">
                <div class="" style="background-color: #f15a01">
                  <img
                    src="img/agoraquadrado.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 50px; background-color: #f15a01" />
                  <h4 class="descricao">Familia</h4>
                  <p class="descricao">
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
                    src="img/agoraquadrado.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 50px; background-color: #f15a01" />

                  <h4 class="descricao">Educação</h4>
                  <!-- <p class="category text-primary">Designer</p> -->
                  <p class="descricao">
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
                <div class="team-player" style="background-color: #f15a01">
                  <img
                    src="img/agoraquadrado.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 50px; background-color: #f15a01" />
                  <h4 class="descricao">Saúde</h4>

                  <p class="descricao">
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
          <!-- <div class="team">
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
          </div> -->
        </div>
      </div>
    </transition>
    <div class="section section-contact-us text-center">
      <div class="container">
        <h2 class="title">Entre em contato com a gente</h2>
        <p class="description">Your project is very important to us.</p>
        <div class="row">
          <div
            class="col-lg-6 text-center ml-auto mr-auto col-md-4"
            style="background-color: ">
            <a href="#carlos" class="btn btn-primary btn-icon btn-round btn-lg"
              ><i class="fab fa-google-plus"></i
            ></a>
            <a href="#carlos" class="btn btn-primary btn-icon btn-round btn-lg"
              ><i class="fab fa-whatsapp"></i
            ></a>
            <a href="#carlos" class="btn btn-primary btn-icon btn-round btn-lg"
              ><i class="fab fa-twitter"></i
            ></a>
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
import { Card, Tabs, TabPane } from '@/components';
export default {
  name: 'landing',
  bodyClass: 'landing-page',
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput,
    CarouselSection,
    Card,
    Tabs,
    TabPane,
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
.descricao {
  color: azure;
  font-weight: bold;
}
</style>
