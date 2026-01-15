<script setup>
import dropdownicon from "../assets/DropdownIcon.vue";
</script>

<template>
  <div class="flex justify-center mt-3.25">
    <div>
      <a href="#">
        <img
          class="w-13 h-13 border border-solid border-white rounded-[10px]"
          src="/src/assets/Nikolay.png"
          alt="Nikolay logo"
        />
      </a>
    </div>
    <div
      class="flex justify-center items-center gap-7.5 text-white/60 border rounded-[60px] px-10 py-2 text-[20px] mx-16"
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
    <div class="border border-white/60 rounded-xl p-2">
      <a
        class="flex justify-center items-center text-white border bg-[#8C45FF]/40 rounded-lg shadow-[inset_0_0_20px_#8C45FF] py-1 px-4.75"
        href="#"
      >
        Join waitlist
      </a>
    </div>
  </div>
</template>
