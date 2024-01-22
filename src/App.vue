<script setup>
import Logo from "./assets/svg/logo.svg";
import More from "./assets/svg/Navbar/bx_bx-menu-alt-right.svg";
import Navbar from "./components/Navbar.vue";
import Screen from "./assets/svg/Landing/screens.svg";
import LgScreen from "./assets/svg/Landing/screen-lg.svg"
</script>

<template>
  <Navbar />
  <div class="grid grid-row-4 justify-items-center">
    <div class="row-span-2">
      <p class="text-5xl w-1/2 text-center mx-auto">
        Work at the speed of thought.
      </p>
      <p class="px-7 py-5 w-1/2 text-center mx-auto">
        Most calendars are designed for teams. Slate is designed for freelancers
        who want a simple way to plan their schedule.
      </p>
    </div>

    <div class="row-span-2 flex flex-col gap-4 mt-6">
      <button class="bg-purple-600 px-7 py-3">Try For Free</button>
      <button class="border-2 px-7 py-3">Learn More</button>
    </div>
    <div>
      <div class="w-full">
        <Screen class="lg:hidden max-w-3xl"/>
    <LgScreen class="hidden lg:block "/>

      </div>
    

    </div>
  
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
