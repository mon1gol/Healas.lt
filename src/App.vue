<template>
  <header class="overflow-hidden md:mx-auto lg:w-[1167px]">
    <div>
      <nav class="fnt-1 text-lg">
        <div class="mt-5 mb-2 flex items-center justify-between px-[15px]">
          <RouterLink to="/"><img class="w-50" src="/Final logo 1 1.png" alt="logo"></RouterLink>
          <div v-show="isMobile" :onclick="showModalNav" class="z-21">
            <HamburgerMenu />
          </div>

          <div v-show="!isMobile" class="z-25 space-x-12.5">
            <RouterLink class="bottom-line" to="/">Home</RouterLink>
            <RouterLink class="bottom-line" to="/">About Us</RouterLink>
            <RouterLink class="bottom-line" to="/">Prices</RouterLink>
            <RouterLink class="bottom-line" to="/">Rules</RouterLink>
            <ButtonComponent :text="'Get Started Now'"></ButtonComponent>
          </div>
        </div>

        <div v-show="isMobile" id="modalNav"
          class="modalnav-nonactive fixed top-0 z-20 flex h-dvh w-lvw flex-col items-center justify-center space-y-5 bg-white text-3xl">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/">About Us</RouterLink>
          <RouterLink to="/">Prices</RouterLink>
          <RouterLink to="/">Rules</RouterLink>
          <ButtonComponent class="text-lg" :text="'Get Started Now'"></ButtonComponent>
        </div>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import ButtonComponent from './components/ButtonComponent.vue';
import HamburgerMenu from './components/HamburgerMenuComponent.vue';

export default {
  components: {
    ButtonComponent,
    RouterLink,
    RouterView,
    HamburgerMenu,
  },
  data() {
    return {
      isMobile: false,
    }
  },
  methods: {
    checkScreenSize(){
      this.isMobile = window.innerWidth < 900
    },
    showModalNav() {
      const modal_nav = document.getElementById('modalNav');
      if (modal_nav.classList.contains('modalnav-nonactive')) {
        modal_nav.classList.remove('modalnav-nonactive');
        modal_nav.classList.add('modalnav-active');
      } else {
        modal_nav.classList.remove('modalnav-active');
        modal_nav.classList.add('modalnav-nonactive');
      }
    },
  },
  mounted() {
    this.checkScreenSize()
    window.addEventListener('resize', this.checkScreenSize)
  },
  beforeUnmount(){
    window.removeEventListener('resize', this.checkScreenSize)
  },
}
</script>

<style>
.bottom-line{
  position: relative;
  display: inline-block;
}
.bottom-line::after{
  content: '';
  position: absolute;
  left: 0;
  bottom: 3px;
  width: 0;
  height: 2px;
  background-image: linear-gradient(90deg, #4499d9 50%, #7367be 100%);
  transition: width 0.3s ease-in-out;
}
.bottom-line:hover::after{
  width: 100%;
}
</style>
