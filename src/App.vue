<script setup>
import Logo from "./assets/svg/logo.svg";
import More from "./assets/svg/Navbar/bx_bx-menu-alt-right.svg";
import Navbar from "./components/Navbar.vue";
import Screen from "./assets/svg/Landing/screens.svg";
import LgScreen from "./assets/svg/Landing/screen-lg.svg";
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

    <div class="row-span-2 flex flex-col gap-4 mt-6 lg:flex-row">
      <button class="bg-purple-600 px-7 py-3">Try For Free</button>
      <button class="border-2 px-7 py-3">Learn More</button>
    </div>
    <div>
      <div class="w-full">
        <Screen
          class="lg:hidden max-w-3xl"
          style="
            background: linear-gradient(
              180deg,
              rgba(30, 30, 30, 0) 0%,
              #0e0e0e 100%
            );
          "
        />
        
        <img src="./assets/svg/Landing/screen-lg.png" class="hidden lg:block pt-8" alt="screens">
      
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>
