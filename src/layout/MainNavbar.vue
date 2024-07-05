<template>
  <navbar
    position="fixed"
    type="primary"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto">
    <template>
      <router-link v-popover:popover1 to="/">
        <img src="img/AGORA.png" alt="deputado do povo" style="height: 60px" />
      </router-link>
      <el-popover
        ref="popover1"
        popper-class="popover"
        placement="bottom"
        width="200"
        trigger="hover">
        <div class="popover-body"></div>
      </el-popover>
    </template>
    <template slot="navbar-menu">
      <li class="nav-item">
        <router-link class="nav-link" to="#povo">
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Com o povo!</p>
        </router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="#projetos">
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Nossos projetos</p>
        </router-link>
      </li>

      <li class="nav-item">
        <a
          class="nav-link"
          href="https://www.creative-tim.com/product/vue-now-ui-kit-pro"
          target="_blank">
          <i class="now-ui-icons arrows-1_share-66"></i>
          <p>Nossos projetos</p>
        </a>
      </li>

      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Follow us on Twitter"
          data-placement="bottom"
          href=""
          target="_blank">
          <i class="fab fa-twitter"></i>
          <p class="d-lg-none d-xl-none">Twitter</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Like us on Facebook"
          data-placement="bottom"
          href=""
          target="_blank">
          <i class="fab fa-facebook-square"></i>
          <p class="d-lg-none d-xl-none">Facebook</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Follow us on Instagram"
          data-placement="bottom"
          href="https://www.instagram.com/CreativeTimOfficial"
          target="_blank">
          <i class="fab fa-instagram"></i>
          <p class="d-lg-none d-xl-none">Instagram</p>
        </a>
      </li>
    </template>
  </navbar>
</template>

<script>
import { DropDown, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number,
  },
  components: {
    //DropDown,
    Navbar,
    //NavLink,
    [Popover.name]: Popover,
  },
};
</script>

<style scoped></style>
