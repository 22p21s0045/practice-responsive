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

        <img
          src="./assets/svg/Landing/screen-lg.png"
          class="hidden lg:block pt-8"
          alt="screens"
        />
      </div>
    </div>
  </div>
  <section>
    <div class="grid grid-cols-6 justify-items-center">
      <p class="col-span-6 text-4xl font-light pt-3">FEATURES</p>
      <p class="col-span-6 text-center w-1/2 pt-3">
        Most calendars are designed for teams. Slate is designed for freelancers
        who want a simple way to plan their schedule.
      </p>
      <img
        src="./assets/section/bot.png"
        alt="dashboard"
        class="col-span-6 justify-items-center p-10"
      />

      <div class="col-span-6 justify-items-center">
        <div class="grid justify-items-center">
          <div class="flex gap-4">
            <img
              src="./assets/icons/Vector.jpg"
              alt=""
              class="flex-initial pt-1"
            />
            <p class="text-2xl flex-initial">A single source of truth</p>
          </div>
          <p class="w-1/2 pt-4">
            When you add work to your Slate calendar we automatically calculate
            useful insights
          </p>
        </div>
        <div class="grid justify-items-center pt-16">
          <div class="flex gap-4">
            <img
              src="./assets/icons/Vector.jpg"
              alt=""
              class="flex-initial pt-1"
            />
            <p class="text-2xl flex-initial">A single source of truth</p>
          </div>
          <p class="w-1/2 pt-4">
            When you add work to your Slate calendar we automatically calculate
            useful insights
          </p>
        </div>
      </div>
      <div class="col-start-3 justify-center col-span-2">
        <div class="flex justify-center flex-col pt-7 w-full">
          <p class="text-3xl m-auto">Contents</p>
          <p class="text-center tracking-normal pt-6">
            We focus on ergonomics and meeting you where you work. It's only a
            keystroke away.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
</style>
