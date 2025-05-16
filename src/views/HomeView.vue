<template>
  <img v-show="!isMobile" class="absolute top-70" src="/cross cropped.png" alt="cross cropped">
  <img class="absolute top-0 left-0 h-[90lvh] w-lvw" src="/backgrounds/back1.png" alt="back1">
  <main>
    <div class="md:grid md:grid-cols-2 md:gap-8.5 md:pt-36 px-[15px] md:mx-auto lg:w-[1167px]">
      <div v-show="!isMobile" class="pb-12.5">
        <div class="mb-[15px] flex items-center gap-7.5">
          <h2 class="fnt-1 text-2xl">Gaming Consoles</h2>
          <img class="object-contain" src="/Arrow right.png" alt="Arrow right">
        </div>
        <div class="mb-9 flex space-x-2 text-4xl lg:text-[68px]">
          <h1 class="fnt-4 lg:font-black">Try It, Rent It, <span class="fnt-1">Save $50!</span></h1>
        </div>
        <section class="fnt-6 mb-8.5 text-lg">
          It is a long established fact that a reader will be distracted by the readable content of a page when looking at
          its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters as
          opposed.
        </section>
        <div class="relative flex justify-center md:justify-start">
          <ButtonComponent class="text-lg" :text="'Get Started Now'"></ButtonComponent>
          <img class="rotate-inf absolute top-20 right-50 object-contain" src="/cross.png" alt="cross">
        </div>
      </div>

      <div class="relative mx-auto aspect-[4/5] w-2/3 max-w-sm md:-top-10 lg:top-10 lg:left-10 lg:scale-140">
        <div class="fnt-1 absolute -top-10 -left-30 z-12 flex w-70 scale-35 space-x-2.5 rounded-[10px] bg-white py-4.5 pr-3 pl-4 shadow-2xl md:-top-5 md:-left-20 md:scale-50">
          <div class="text-sm ">
            <h1 class="mb-1.5">Sony Dualshock 4 Wireless Controller </h1>
            <h2 class="mb-1 fnt-4">$50 Per Hour</h2>
            <div class="flex space-x-1.5">
              <img class="object-contain" src="/character/Stars.png" alt="Stars">
              <h3>125+Review</h3>
            </div>
          </div>
          <img class="w-[90%] object-contain" src="/character/VR.png" alt="VR">
        </div>

        <div class="fnt-1 absolute -bottom-5 left-25 z-14 flex w-70 scale-35 space-x-2.5 rounded-[10px] bg-white py-4.5 pr-4 pl-3 shadow-2xl md:-bottom-0 md:left-60 md:scale-50">
          <img class="object-contain" src="/character/gamepad.png" alt="gamepad">
          <div class="text-sm ">
            <h1 class="mb-1.5">Sony Dualshock 4 Wireless Controller </h1>
            <h2 class="mb-1 fnt-4">$50 Per Hour</h2>
            <div class="flex space-x-1.5">
              <img class="object-contain" src="/character/Stars.png" alt="Stars">
              <h3>125+Review</h3>
            </div>
          </div>
        </div>

        <img class="absolute top-0 -left-5 z-10 h-full w-full object-contain" src="/character/Vector 1-1.png"
        alt="Vector 1-1">
        <img class="absolute top-0 left-5 z-10 h-full w-full object-contain" src="/character/Vector 1-2.png"
        alt="Vector 1-2">
        <img class="absolute top-0 left-0 z-11 h-full w-full object-contain" src="/character/Vector 2.png" alt="Vector 2">
        <img class="object-appearance-x absolute -top-25 left-5 z-12 h-full w-full object-contain" src="/character/Vector 3.png"
        alt="Vector 3">
        <img class="object-appearance absolute -top-2 -left-5 z-13 h-full w-full object-contain" src="/character/Vector 4.png"
        alt="Vector 4">
        <img v-show="!isMobile" class="absolute -right-40 top-30 scale-80" src="/DOTS.png" alt="DOTS">
      </div>

      <div v-show="isMobile" class="pb-12.5">
        <h2 class="fnt-1 mb-[15px] text-2xl">Gaming Consoles</h2>
        <div class="mb-9 flex space-x-2 text-4xl lg:text-[68px]">
          <h1 class="fnt-4">Try It, Rent It, <span class="fnt-1">Save $50!</span></h1>
        </div>
        <section class="fnt-6 mb-8.5 text-lg">
          It is a long established fact that a reader will be distracted by the readable content of a page when looking at
          its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters as
          opposed.
        </section>
        <div class="flex justify-center md:justify-start">
          <ButtonComponent class="text-lg" :text="'Get Started Now'"></ButtonComponent>
        </div>
      </div>
    </div>

    <div class="pb-12.5 md:mt-34 md:grid md:grid-cols-2 md:gap-8.5 px-[15px] md:mx-auto lg:w-[1167px]">
      <div class="relative mx-auto aspect-[4/5] w-2/3 max-w-sm scale-75 lg:-left-5 lg:top-20">
        <img class="absolute top-35 left-0 z-10 h-full w-full scale-200 object-contain" src="/screenman/back.png"
          alt="back">
        <img class="absolute top-85 left-0 z-11 h-full w-full object-contain" src="/screenman/shadow.png" alt="shadow">
        <img class="swimming-inf absolute top-5 left-10 z-12 h-full w-full object-contain" src="/screenman/screen.png" alt="screen">
        <img class="absolute top-65 -left-20 z-13 h-full w-full object-contain" src="/screenman/men.png" alt="men">
      </div>
      <div>
        <h2 class="fnt-1 mt-50 mb-[15px] text-2xl">About VR Glasses</h2>
        <div class="mb-9 flex space-x-2 text-4xl lg:text-[68px]">
          <h1 class="fnt-4">The New VR Glasses Series</h1>
        </div>
        <section class="fnt-6 mb-8.5 text-lg">
          It is a long established fact that a reader will be distracted by the readable content of a page when looking at
          its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters as
          opposed.
        </section>
        <div class="flex justify-center md:justify-start">
          <ButtonComponent class="text-lg" :text="'Get Started Now'"></ButtonComponent>
        </div>
      </div>
    </div>

    <div class="bg-[url(/backgrounds/back3.png)] z-1 bg-no-repeat w-screen bg-cover bg-center">
      <div class="pb-25 pt-12.5 md:mt-34 md:grid md:grid-cols-2 md:gap-8.5 px-[15px] md:mx-auto lg:w-[1167px]">
        <div v-show="!isMobile">
          <h2 class="fnt-1 mt-15 mb-[15px] text-2xl">About XBOX, PS</h2>
          <div class="mb-9 flex space-x-2 text-4xl lg:text-[68px]">
            <h1 class="fnt-4">The New Xbox, Ps Series</h1>
          </div>
          <section class="fnt-6 mb-8.5 text-lg">
            It is a long established fact that a reader will be distracted by the readable content of a page when looking at
            its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters as
            opposed.
          </section>
          <div class="relative flex justify-center md:justify-start">
            <ButtonComponent class="text-lg" :text="'Get Started Now'"></ButtonComponent>
            <img class="absolute right-30 -top-10" src="/Arrow left.png" alt="Arrow left">
          </div>
        </div>

        <div class="relative mx-auto aspect-[4/5] w-2/3 max-w-sm">
          <img class="absolute top-0 left-0 z-10 h-full w-full scale-130 object-contain" src="/gamepad/back.png"
            alt="back">
          <img class="absolute top-0 left-20 z-11 h-full w-full scale-50 object-contain" src="/gamepad/leaf1.png"
            alt="leaf1">
          <img class="absolute -top-10 -left-20 z-11 h-full w-full scale-50 object-contain" src="/gamepad/leaf2.png"
            alt="leaf2">
          <img class="absolute top-70 -right-20 z-11" src="/DOTS.png" alt="DOTS">
          <img class="absolute top-0 left-0 z-12 h-full w-full scale-120 object-contain" src="/gamepad/cloud.png"
            alt="cloud">
          <img class="rotate-inf absolute -top-35 left-30 z-13 h-full w-full scale-30 object-contain" src="/gamepad/gear_big.png"
            alt="gear_big">
          <img class="rotate-inf absolute -top-20 left-10 z-13 h-full w-full scale-20 object-contain" src="/gamepad/gear_small.png"
            alt="gear_small">
          <img v-show="!isMobile" class="swimming-inf absolute top-25 left-0 z-14 h-full w-full object-contain" src="/gamepad/gamepad.png" alt="gamepad">
          <img v-show="isMobile" class="absolute top-25 left-0 z-14 h-full w-full object-contain" src="/gamepad/gamepad.png" alt="gamepad">
          <img v-show="isMobile" class="absolute -top-10 -left-15 z-15 h-full w-full scale-50 object-contain" src="/gamepad/man1.png"
            alt="man1">
          <img v-show="isMobile" class="absolute top-35 left-35 z-15 h-full w-full scale-50 object-contain" src="/gamepad/man2.png"
            alt="man2">
        </div>
        <div v-show="isMobile">
          <h2 class="fnt-1 mt-15 mb-[15px] text-2xl">About XBOX, PS</h2>
          <div class="mb-9 flex space-x-2 text-4xl lg:text-[68px]">
            <h1 class="fnt-4">The New Xbox, Ps Series</h1>
          </div>
          <section class="fnt-6 text-lg mb-8.5">
            It is a long established fact that a reader will be distracted by the readable content of a page when looking at
            its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters as
            opposed.
          </section>
          <div class="flex justify-center md:justify-start">
            <ButtonComponent class="text-lg" :text="'Get Started Now'"></ButtonComponent>
          </div>
        </div>
      </div>
    </div>


    <div class="pb-12.5 px-[15px] md:mx-auto lg:w-[1167px]">
      <h2 class="fnt-1 mt-15 mb-[15px] text-center text-2xl">Our Pricing</h2>
      <div class="mb-9 text-4xl lg:text-[68px]">
        <h1 class="fnt-4 text-center">Choose Your Plan</h1>
      </div>
      <div class="md:align-items-center space-y-5 md:mx-auto md:grid md:grid-cols-2 md:justify-items-center md:gap-10 lg:flex lg:grid-cols-3 lg:items-center lg:space-y-0">
        <div class="bg-7 w-full rounded-[20px] px-10 pt-9 pb-11.5 lg:h-[506px]">
          <h2 class="fnt-1 mb-[15px] text-center text-3xl lg:text-left">Basic</h2>
          <div class="text-lg mb-5">
            <h1 class="fnt-4 text-center text-5xl lg:text-left">$50.00 <span class="text-lg">/ Per Hour</span></h1>
          </div>
          <CheckBoxList :checkList="['10 users included', '2 GB of storage', 'Email support', 'Help center access', '10 users included']" :isBlack="true"/>
          <div class="flex justify-center mt-5">
            <ButtonComponent class="w-full" :text="'Select This Plan'"/>
          </div>
        </div>

        <div class="cards-grad-black relative w-full rounded-[20px] px-10 pt-9 pb-11.5 text-white lg:h-[606px]">
          <img class="object-contain absolute right-6 top-6" src="/badge.png" alt="badge">
          <h2 class="text-3xl text-center mb-[15px] lg:text-left">Standard</h2>
          <div class="text-lg mb-5">
            <h1 class="fnt-4 text-center text-5xl lg:text-left">$95.00 <span class="text-lg">/ Per Hour</span></h1>
          </div>
          <CheckBoxList :checkList="['10 users included', '2 GB of storage', 'Email support', 'Help center access', '10 users included']" :isBlack="false"/>
          <div class="flex justify-center mt-18">
            <ButtonComponent class="w-full z-10" :text="'Select This Plan'"/>
          </div>
          <img class="absolute bottom-0 left-0 object-cover" src="/checkDecor.png" alt="checkDecor">
        </div>

        <div class="bg-7 w-full rounded-[20px] px-10 pt-9 pb-11.5 lg:h-[506px]">
          <h2 class="fnt-1 text-3xl text-center mb-[15px] lg:text-left">Premium</h2>
          <div class="text-lg mb-5">
            <h1 class="fnt-4 text-center text-5xl lg:text-left">$120.00 <span class="text-lg">/ Per Hour</span></h1>
          </div>
          <CheckBoxList :checkList="['10 users included', '2 GB of storage', 'Email support', 'Help center access', '10 users included']" :isBlack="true"/>
          <div class="flex justify-center mt-5">
            <ButtonComponent class="w-full" :text="'Select This Plan'"/>
          </div>
        </div>
      </div>
    </div>
  </main>
  <footer class="border-footer">
    <div class="flex flex-col items-center pt-6 pb-5 md:flex-row md:justify-between lg:mx-auto lg:w-[1167px]">
      <img class="w-50 mb-5" src="/Final logo 1 1.png" alt="logo">
      <section v-show="!isMobile" class="fnt-6 text-sm mb-8.5 md:mb-0">
        Copyright © 2025 HEALAS.LT. All Rights Reserved.
      </section>
      <div class="mb-5 flex space-x-1">
        <div class="relative hover:invert hover:cursor-pointer duration-600">
          <img class="z-2" src="/contacts/contact back.png" alt="contact back">
          <a href=""><img class="z-1 absolute inset-0 m-auto size-5 object-contain" src="/contacts/github.png" alt="github"></a>
        </div>
        <div class="relative hover:invert hover:cursor-pointer duration-600">
          <img class="z-2" src="/contacts/contact back.png" alt="contact back">
          <a href="https://t.me/monolog_it"><img class="z-1 absolute inset-0 m-auto size-5 object-contain" src="/contacts/telegram.png" alt="telegram"></a>
        </div>
        <div class="relative hover:invert hover:cursor-pointer duration-600">
          <img class="z-2" src="/contacts/contact back.png" alt="contact back">
          <a href="https://www.figma.com/design/vgrMGMBzIjMdYDi5z3GY1M/Gogames?node-id=4-2731&t=vfFfs6wrM6hVNEa5-0"><img class="z-1 absolute inset-0 m-auto size-5 object-contain" src="/contacts/figma.png" alt="figma"></a>
        </div>
      </div>
      <section v-show="isMobile" class="fnt-6 text-sm mb-8.5">
        Copyright © 2025 HEALAS.LT. All Rights Reserved.
      </section>
    </div>
  </footer>
</template>

<script>
import ButtonComponent from '@/components/ButtonComponent.vue';
import CheckBoxList from '@/components/CheckBoxListComponent.vue';

export default {
  components: {
    ButtonComponent,
    CheckBoxList,
  },
  data() {
    return {
      isMobile: false,
    }
  },
  methods: {
    checkScreenSize(){
      this.isMobile = window.innerWidth < 768
    },
  },
  mounted() {
    this.checkScreenSize()
    window.addEventListener('resize', this.checkScreenSize)
  },
  beforeUnmount() {
    window.removeEventListener('resize', this.checkScreenSize)
  },
}
</script>

<style>
.cards-grad-black{
  background-image: linear-gradient(#446381 60%, #826F8C 100%);
}
.border-footer{
  border-top-color: #816F8C;
  border-top-width: 1.5px;
}
.rotate-inf {
  animation: spin 6s linear infinite;
}
@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
.swimming-inf{
  animation: swimming 3s ease-in-out infinite;
}
@keyframes swimming{
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
  100% {
    transform: translateY(0);
  }
}
.object-appearance{
  animation: appearance 1.5s ease;
}
.object-appearance-x{
  opacity: 0;
  transform-origin: center;
  animation: appearance-x 1.5s ease;
  animation-delay: 1.5s;
  animation-fill-mode: forwards;
}
@keyframes appearance {
  0%{
    opacity: 0;
    transform: translateY(50px);
  }
  100%{
    opacity:1;
    transform: translateY(0);
  }
}
@keyframes appearance-x {
  0%{
    opacity: 0;
    transform: scaleX(0);
  }
  100%{
    opacity:1;
    transform: scaleX(100%);
  }
}
</style>
