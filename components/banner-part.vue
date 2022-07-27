<template>
  <section class="bg-amber-200 py-6">
    <div class="grid grid-cols-5 items-center gap-10 my-40 lg:my-0">
      <div class="col-span-3 mt-8">
        <img
          class="w-screen lg:w-[700px]"
          src="../assets/images/fashion-model.png"
          alt="fashion model"
        />
      </div>
      <div class="col-span-2">
        <h1 class="font-bold md:text-3xl pr-5 my-3">New Trends For All</h1>
        <h2 class="font-bold md:text-3xl pr-5 my-3">Fashion Week</h2>
        <p
          class="px-2 sm:border-2 md:shadow-lg sm:hover:bg-slate-700 sm:text-lime-100 sm:cursor-pointer sm:rounded-full sm:bg-slate-500 sm:w-[208px]"
        >
          Find What Ever You Want
        </p>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "banner-part",
  data() {
    return {};
  },
  methods: {
    showMenuItems() {},
  },
});
</script>
