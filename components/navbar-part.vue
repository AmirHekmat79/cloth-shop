<template>
  <nav class="bg-slate-500 py-9 px-12">
    <div class="flex justify-around items-center mt-3">
      <div class="flex">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-11 text-red-200"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"
          />
        </svg>
        <span class="mx-6 hover:text-gray-300 text-lime-50 cursor-pointer"
          >Fashion</span
        >
      </div>
      <div class="lg:hidden ml-auto mr-0" @click="showMenuItems()">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-11 mr-6 text-lime-50 cursor-pointer transition-all ease-in duration-300"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>
      </div>
      <ul
        class="hidden absolute lg:static top-28 right-0 lg:top-0 flex-col lg:flex-row lg:flex items-center"
        id="Menu"
      >
        <li
          class="hover:text-gray-300 text-black my-2 mr-9 lg:my-0 lg:text-lime-50 lg:mr-32"
        >
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li
          class="hover:text-gray-300 text-black my-2 mr-9 lg:my-0 lg:text-lime-50 lg:mr-32"
        >
          <NuxtLink to="/">Products</NuxtLink>
        </li>
        <li
          class="hover:text-gray-300 text-black my-2 mr-9 lg:my-0 lg:text-lime-50 lg:mr-32"
        >
          <NuxtLink to="/">Awards</NuxtLink>
        </li>
        <li
          class="hover:text-gray-300 text-black my-2 mr-9 lg:my-0 lg:text-lime-50 lg:mx-8 lg:bg-slate-400 lg:rounded-full lg:p-2"
        >
          <NuxtLink to="/">Login</NuxtLink>
        </li>
        <li
          class="hover:text-gray-300 text-black my-2 mr-9 lg:my-0 lg:text-lime-50 lg:mx-8 lg:bg-slate-400 lg:rounded-full lg:p-2"
        >
          <NuxtLink to="/">Sign Up</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "navbar-part",
  data() {
    return {};
  },
  methods: {
    showMenuItems() {
      const menuBar = document.querySelector("#Menu");
      if (menuBar?.classList.contains("hidden")) {
        menuBar.classList.remove("hidden");
      } else {
        menuBar?.classList.add("hidden");
      }
    },
  },
});
</script>
