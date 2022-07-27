<template>
  <section class="py-6 bg-slate-200">
    <div class="flex flex-wrap justify-center mx-auto items-center gap-5">
      <div class="text-center p-8">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-44 w-44 mx-auto my-3 text-green-500"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"
          />
        </svg>
        <h1 class="my-3 font-bold">Award Sign</h1>
        <p class="my-4">We Had Achieved Too Many Awards Through These Years</p>
      </div>
      <div class="text-center p-8">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-44 w-44 mx-auto text-red-700"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z"
            clip-rule="evenodd"
          />
        </svg>
        <h1 class="my-3 font-bold">Customer satisfaction</h1>
        <p class="my-4">We Had Achieved Too Many Awards Through These Years</p>
      </div>
      <div class="text-center p-8">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-44 w-44 mx-auto text-blue-400"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
          />
        </svg>
        <h1 class="my-3 font-bold">Reliable Purchase</h1>
        <p class="my-4">We Had Achieved Too Many Awards Through These Years</p>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "awards-part",
  data() {
    return {};
  },
  methods: {},
});
</script>
