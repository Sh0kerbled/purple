<script setup>
import dropdownicon from "../assets/DropdownIcon.vue";
</script>

<template>
  <div class="flex justify-center items-center my-3.25">
    <div>
      <a href="#">
        <img
          class="w-10.5 h-10.5 border border-solid border-white/15 rounded-[10px]"
          src="/src/assets/Nikolay.png"
          alt="Nikolay logo"
        />
      </a>
    </div>
    <div
      class="flex justify-center items-center gap-7.5 text-white/60 border border-white/15 rounded-[60px] px-10 py-3 text-[13px] mx-18.5"
    >
      <a href="#" class="flex items-center gap-0.75"
        >Features <dropdownicon
      /></a>
      <a href="#">Developers</a>
      <a href="#" class="flex items-center gap-0.75"
        >Company <dropdownicon
      /></a>
      <a href="#">Blog</a>
      <a href="#">Changelog</a>
    </div>
    <div class="border border-white/15 rounded-xl p-1.5">
      <a
        class="flex justify-center items-center text-white border border-[white]/40 bg-[#8C45FF]/40 rounded-lg shadow-[inset_0_0_10px_#8C45FF] py-0.5 px-3.75"
        href="#"
      >
        Download
      </a>
    </div>
  </div>
</template>
