<template>
  <footer class="py-14 bg-slate-500 px-32">
    <h1 class="text-4xl text-white">Fashion</h1>
    <div class="lg:grid lg:grid-cols-12 flex flex-col">
      <div class="col-span-3">
        <ul class="flex flex-col text-center">
          <li class="my-3">
            <h1 class="my-3 text-2xl text-amber-300">PLATFORM</h1>
          </li>
          <li class="hover:text-gray-300 my-2">
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li class="hover:text-gray-300 my-2">
            <NuxtLink to="/">Products</NuxtLink>
          </li>
          <li class="hover:text-gray-300 my-2">
            <NuxtLink to="/">Awards</NuxtLink>
          </li>
          <li class="hover:text-gray-300 my-2">
            <NuxtLink to="/">Login</NuxtLink>
          </li>
          <li class="hover:text-gray-300 my-2">
            <NuxtLink to="/">Sign Up</NuxtLink>
          </li>
        </ul>
      </div>

      <div class="col-span-3">
        <ul class="flex flex-col text-center">
          <li class="my-3">
            <h1 class="my-5 text-2xl text-amber-300">COMPANY</h1>
          </li>
          <li class="hover:text-gray-300 my-3">
            <NuxtLink to="/">Careers</NuxtLink>
          </li>
          <li class="hover:text-gray-300 my-3">
            <NuxtLink to="/">Contact</NuxtLink>
          </li>
        </ul>
      </div>

      <div class="col-span-3">
        <ul class="flex flex-col text-center">
          <li class="my-3">
            <h1 class="my-5 text-2xl text-amber-300">LEGAL</h1>
          </li>
          <li class="hover:text-gray-300 my-3">
            <NuxtLink to="/">Privacy Policy</NuxtLink>
          </li>
          <li class="hover:text-gray-300 my-3">
            <NuxtLink to="/">Terms & Conditions</NuxtLink>
          </li>
        </ul>
      </div>

      <div class="col-span-3 text-center">
        <h1 class="my-5 text-2xl text-amber-300">SUBSCRIBE</h1>

        <p class="text-lg">
          Subscribe to stay tuned for news and the latest updates. No junk and
          no spam. Only our best stuff.
        </p>
        <div class="flex justify-center items-center mt-10">
          <input
            type="email"
            placeholder="Email"
            class="px-5 py-3 rounded-md focus:ring-4 focus:ring-blue-600"
          />
          <button
            class="text-white text-xs py-3 mx-4 px-4 rounded-md uppercase bg-zinc-900 hover:bg-slate-900"
          >
            Send
          </button>
        </div>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "footer-part",
  data() {
    return {};
  },
  methods: {},
});
</script>
