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
          <div class="col-md-8 ml-auto mr-auto text-center">
            <transition appear="">
              <h2
                class=""
                id="povo"
                style="
                  text-transform: uppercase;
                  color: aliceblue;
                  font-weight: bold;
                ">
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
                style="
                  background-image: url('img/patriota.gif');
                  border-radius: 10px;
                "></div>
            </div>
            <div class="col-md-6">
              <h1
                style="
                  margin-top: 3cm;
                  color: #ffff;
                  font-weight: bold;
                  text-align: center;
                  background-color: #f15a01;
                  padding: 20px;
                  border-radius: 10px;
                  font-size: 250%;
                ">
                O povo pediu, a mudança chegou!!
              </h1>
              <p
                style="
                  color: #ffff;
                  text-align: center;
                  font-weight: bold;
                  background-color: #00bac1;
                  padding: 30px 30px 40px;
                  border-radius: 10px;
                ">
                The Arctic Ocean freezes every winter and much of the sea-ice
                then thaws every summer, and that process will continue whatever
                happens with climate change. Even if the Arctic continues to be
                <br />
                <br />

                <router-link to="#projetos" class="botao"
                  >Plano de governo</router-link
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="section" style="background-color: #00bac1">
      <div class="container">
        <h2
          class="title"
          style="font-size: 300%; color: #f15a01; text-align: center">
          Plano de governo
        </h2>
        <p class="texto-box-plano-governo">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat
        </p>
        <br />
        <br />
        <div class="row" style="margin-bottom: 1cm">
          <div class="coluna-md-4 box-plano-governo">
            <h1 class="planoh1">.01</h1>
            <h3 class="planoh3">Avante Família</h3>
            <p class="texto-box-plano-governo">
              hwefguiwefhwjnbncwuidwe dfwecfwe fuwedf weduhhq fi wf fuhfdhwf wf
              wf9w fw98
            </p>
          </div>

          <div class="coluna-md-4 box-plano-governo">
            <h1 class="planoh1">.02</h1>
            <h3 class="planoh3">Avante Educação</h3>
            <p class="texto-box-plano-governo">
              hwefguiwefhwjnbncwuidwe dfwecfwe fuwedf weduhhq fi wf fuhfdhwf wf
              wf9w fw98
            </p>
          </div>
          <div class="coluna-md-4 box-plano-governo">
            <h1 class="planoh1">.03</h1>
            <h3 class="planoh3">Avante Saúde</h3>
            <p class="texto-box-plano-governo">
              hwefguiwefhwjnbncwuidwe dfwecfwe fuwedf weduhhq fi wf fuhfdhwf wf
              wf9w fw98
            </p>
          </div>
        </div>
        <div class="row">
          <div class="coluna-md-4 box-plano-governo">
            <h1 class="planoh1">.04</h1>
            <h3 class="planoh3">Avante Mulheres</h3>
            <p class="texto-box-plano-governo">
              hwefguiwefhwjnbncwuidwe dfwecfwe fuwedf weduhhq fi wf fuhfdhwf wf
              wf9w fw98
            </p>
          </div>

          <div class="coluna-md-4 box-plano-governo">
            <h1 class="planoh1">.05</h1>
            <h3 class="planoh3">Avante Segurança</h3>
            <p class="texto-box-plano-governo">
              hwefguiwefhwjnbncwuidwe dfwecfwe fuwedf weduhhq fi wf fuhfdhwf wf
              wf9w fw98
            </p>
          </div>
          <div class="coluna-md-4 box-plano-governo">
            <h1 class="planoh1">.06</h1>
            <h3 class="planoh3">Avante Emprego</h3>
            <p class="texto-box-plano-governo">
              hwefguiwefhwjnbncwuidwe dfwecfwe fuwedf weduhhq fi wf fuhfdhwf wf
              wf9w fw98
            </p>
          </div>
        </div>
      </div>
    </div>
    <transition appear="">
      <div
        class="section1 section-team text-center"
        style="background-image: url('img/agorabanner.png')">
        <h2 class="title" style="color: #f15a01; font-size: 300%">
          POR ONDE VAMOS COMEÇAR
        </h2>
        <p class="texto-box-plano-governo">
          heejiojgoieg uioeherguiero eiuhjerio geruig ieurogh iuerhg ierjhg
          euirohg eruiog herouih goeuirg erouigj ioerg erioj gjeogjjg
        </p>
        <div class="container">
          <div class="team">
            <div class="row">
              <div class="col-md-4" style="">
                <div class="team-player" style="background-color: #f15a01">
                  <img
                    src="img/familia.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 10px" />

                  <h4 class="descricao">Familia</h4>
                  <hr />
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
                    src="img/educacao.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 10px" />

                  <h4 class="descricao">Educação</h4>
                  <hr />
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
                    src="img/saude.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 10px; background-color: #f15a01" />
                  <h4 class="descricao">Saúde</h4>
                  <hr />
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
          <div class="team">
            <div class="row">
              <div class="col-md-4" style="">
                <div class="team-player" style="background-color: #f15a01">
                  <img
                    src="img/familia.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 10px" />

                  <h4 class="descricao">Familia</h4>
                  <hr />
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
                    src="img/educacao.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 10px" />

                  <h4 class="descricao">Educação</h4>
                  <hr />
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
                    src="img/saude.png"
                    alt="Thumbnail Image"
                    class=""
                    style="padding: 10px; background-color: #f15a01" />
                  <h4 class="descricao">Saúde</h4>
                  <hr />
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
        </div>
      </div>
    </transition>
    <div
      class="section section-contact-us text-center"
      style="background-color: #00bac1">
      <div class="container">
        <h2 class="title">
          Entre em contato<br />
          com a gente
        </h2>
        <div class="row">
          <div
            class="col-lg-6 text-center ml-auto mr-auto col-md-4"
            style="margin-top: 1cm">
            <a href="#carlos" class="botao wppbtn"
              ><i class="fab fa-whatsapp"></i> WhatsApp
            </a>
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
    //CarouselSection,
    // Card,
    // Tabs,
    // TabPane,
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
  font-weight: bolder;
  text-align: center;
  margin-left: 10px;
}
/* plano de governo style */
.planoh1,
.planoh3 {
  text-align: center;
  color: orangered;
}
.planoh3 {
  font-weight: bold;
}
.box-plano-governo {
  border-radius: 10px;

  background-color: #dfdfdf;
}
.texto-box-plano-governo {
  color: black;
  font-weight: 500;
  text-align: center;
}
.coluna-md-4 {
  -webkit-box-flex: 0;
  flex: 0 0 33.333333%;
  max-width: 32%;
  margin: 5px;
}
hr {
  background-color: #dfdfdf;
  max-width: 300px;
  border-radius: 10px;
  position: relative;
  height: 1px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}
.botao {
  border-radius: 20px;
  background-color: #f15a01;
  font-weight: bold;
  color: #fff;
  padding: 15px;
}
.wppbtn {
  padding: 20px 40px;
}
</style>
