<script setup>
import { ref } from 'vue';
let showRedbg = ref(false);

document.addEventListener("scroll", function(){
  let bodyTopPosition = document.body.getBoundingClientRect().top;
  if(bodyTopPosition<-150){
    showRedbg.value = true;
  }else{
    showRedbg.value=false;
  }
});
</script>

<template>
  <div>
    <div>
      <nav :class="{ 'sm:bg-transparent sm:shadow-none' : !showRedbg }" class="p-2 bg-red-500 sm:flex sm:justify-between sm:items-center sm:px-0 sm:py-0 z-10 transition-colors duration-500">
      <div class="grid grid-cols-2 gap-5">
        <a href="#" class="p-5 font-bold text-lg">Portfo<span>lio.</span></a>
        <ul class="md:flex lg:p-5 sm:p-0 hidden cursor-pointer">
          <li>
            <router-link
            :to="{ name: 'Search' }"
            class="p-5 text-white hover:text-black sm:font-xs"
            >Home</router-link
          >
          <router-link
            :to="{ name: 'Search' }"
            class="p-5 text-white hover:text-black sm:font-xs"
            >About</router-link
          >
          <router-link
            :to="{ name: 'Search' }"
            class="p-5 text-white hover:text-black sm:font-xs"
            >Services</router-link
          >
          <router-link
            :to="{ name: 'Search' }"
            class="p-5 text-white hover:text-black sm:font-xs"
            >Skills</router-link
          >
          <router-link
            :to="{ name: 'Search' }"
            class="p-5 text-white hover:text-black sm:font-xs"
            >Teams</router-link
          >
          <router-link
            :to="{ name: 'Search' }"
            class="p-5 text-white hover:text-black sm:font-xs"
            >Contact</router-link
          >
          </li>
        </ul>
      </div>
    </nav>
    </div>
    <button
          class="col-start-11 block md:hidden py-3 px-4 mx-2 rounded focus:outline-none hover:bg-grey-200 group"
        >
          <div class="w-5 h-1 bg-gray-600 mb-1"></div>
          <div class="w-5 h-1 bg-gray-600 mb-1"></div>
          <div class="w-5 h-1 bg-gray-600"></div>
          <div
            class="absolute top-0 right-full h-screen w-8/12 bg-white border opacity-0 group-focus:right-0 group-focus:opacity-100 transition-all duration-300"
          >
            <ul
              class="flex flex-col items-center w-full text-base cursor-pointer pt-10"
            >
              <router-link
                :to="{ name: 'Search' }"
                class="hover:bg-blue-300 py-4 px-6 w-full"
                >Home</router-link
              >
              <router-link
                :to="{ name: 'Search' }"
                class="hover:bg-blue-300 py-4 px-6 w-full"
                >About</router-link
              >
              <router-link
                :to="{ name: 'Search' }"
                class="hover:bg-blue-300 py-4 px-6 w-full"
                >Services</router-link
              >
              <router-link
                :to="{ name: 'Search' }"
                class="hover:bg-blue-300 py-4 px-6 w-full"
                >Skills</router-link
              >
              <router-link
                :to="{ name: 'Search' }"
                class="hover:bg-blue-300 py-4 px-6 w-full"
                >Contact</router-link
              >
            </ul>
          </div>
        </button>
  </div>
</template>
