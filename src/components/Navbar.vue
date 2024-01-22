<script setup>
import Logo from '../assets/svg/logo.svg'
import More from '../assets/svg/Navbar/bx_bx-menu-alt-right.svg'


</script>

<style>

</style>
<template>
  <div class="grid grid-cols-2 p-5 md:grid-cols-3">
<Logo/>
<div class="hidden md:flex text-white p-5 gap-6 lg:gap-20 ">
<button>Home</button>
<button>Product</button>
<button>About</button>
<button>Contact</button>
</div>
<div class="p-5 col-span-1 flex justify-between items-center lg:justify-end ">
  <button class="text-white border-solid border-2 p-8 w-44 flex items-center justify-center h-4 ">
   Login
  </button>
  <button class="md:hidden ml-5">
    <More/>
  </button>
</div>

 </div>
</template>

