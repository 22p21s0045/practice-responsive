<script setup>
import Logo from "./assets/svg/logo.svg";
import More from "./assets/svg/Navbar/bx_bx-menu-alt-right.svg";
import Navbar from "./components/Navbar.vue";
</script>

<template>
  <Navbar />
  <div class="grid grid-row-4 justify-items-center ">
    <div class="row-span-2 ">
      <p class="text-5xl w-1/2  text-center mx-auto">Work at the speed of thought.</p>
    <p class="px-7 py-5">
      Most calendars are designed for teams. Slate is designed for freelancers
      who want a simple way to plan their schedule.
    </p>

    </div>
  
    <div class="row-span-2">
      <button>
        Try For Free
      </button>
      <button>Learn More</button>
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
