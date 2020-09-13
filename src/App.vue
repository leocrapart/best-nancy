<template>
  <div class="px-40 bg-gray-100 h-screen">
    <div class="flex justify-start">

      <router-link to="/">
        <div class="w-40">
          <div class="relative" style="padding-bottom: 50%">
            <img src="@/assets/logo_nancy_no_bg.png" alt="Logo BEST Nancy"
              class="absolute h-full w-full object-cover ">
          </div>
        </div>
      </router-link>

      <div class="flex justify-end w-full items-center space-x-8 text-gray-500 text-lg font-medium">
        <router-link to="/events" class="hover:text-gray-700 ">
          Evènements
        </router-link>
        <router-link to="/about" class="hover:text-gray-700 ">
          Infos
        </router-link>
        <a href="https://www.facebook.com/BEST-Nancy-437026863023108/">
          <svg class=" h-8 w-8 fill-current hover:text-gray-700 "
            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
          	<path d="M17 1H3c-1.1 0-2 .9-2 2v14c0 1.101.9 2 2 2h7v-7H8V9.525h2v-2.05c0-2.164 1.212-3.684 3.766-3.684l1.803.002v2.605h-1.197c-.994 0-1.372.746-1.372 1.438v1.69h2.568L15 12h-2v7h4c1.1 0 2-.899 2-2V3c0-1.1-.9-2-2-2z"/>
          </svg>
        </a>
      </div>
    </div>
    <div class="border-b bg-gray-200 my-2">

    </div>

    <router-view />
  </div>
</template>
