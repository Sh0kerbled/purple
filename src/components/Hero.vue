<script setup>
import MainPage from "../assets/MainPage.vue";
</script>

<template>
  <div class="w-full border border-t-white/15 grid justify-items-center">
    <div
      class="inline-flex border border-white/15 gap-2 px-4 py-2 rounded-[50px] mt-22.5 mb-3.5"
    >
      <div
        class="border border-none bg-[#9855FF] px-1.5 font-bold rounded-[40px]"
      >
        NEW
      </div>
      <div class="text-[#9855FF] leading-6.5">
        Latest integration just arrived
      </div>
    </div>
    <div class="w-146.5 grid justify-items-center">
      <div class="text-[76px] leading-18.5 font-bold text-white text-center">
        Boost your
        <p
          class="bg-linear-to-t from-[#B372CF] to-white bg-clip-text text-transparent h-21"
        >
          playtime with us
        </p>
      </div>
      <div class="flex text-center text-white text-[21px] pt-4">
        Maximize your playtime effortlessly with our powerful hour boosting app
      </div>
      <div class="border border-white/15 p-2 rounded-xl mt-4 mb-8 z-20">
        <button class="bg-white px-4 py-2 rounded-lg z-30">Download</button>
      </div>
    </div>
    <div
      class="w-280 h-160 bg-white/10 rounded-[30px] flex justify-center inset-0 shadow-[0px_0px_1500px_rgba(140,69,255,.90)]"
    >
      <MainPage />
    </div>
  </div>
</template>
