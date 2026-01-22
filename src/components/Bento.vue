<script setup>
import SeoVisual from "../assets/SeoVisual.vue";
import Game from "../assets/Game.vue";
import Purple from "../assets/Purple.vue";
import Triangle from "../assets/Triangle.vue";
</script>

<template>
  <div class="grid justify-center text-white text-[32px]">
    <div class="w-138.25 text-center mx-auto" data-aos="fade-down">
      Harness our powerful tool, making hour boosting intuitive and effective
      for all skill levels.
    </div>
    <div class="flex gap-2.5 pt-8">
      <div
        data-aos="fade-right"
        data-aos-delay="800"
        data-aos-duration="1000"
        class="flex flex-wrap items-center justify-center w-86.5 h-100 border-white/15 rounded-xl border"
      >
        <SeoVisual />
        <div class="text-white text-[16px] w-64.75">
          SEO goal setting
          <p class="text-white/70">
            Helps you set and achieve SEO goals with guided assistance.
          </p>
        </div>
      </div>
      <div
        data-aos="fade-left"
        data-aos-delay="900"
        data-aos-duration="1000"
        class="flex flex-wrap w-186 h-100 shadow-[inset_0_-220px_260px_-80px_rgba(54,23,100,1)]"
      >
        <Game class="ml-auto mt-auto" />
        <Purple class="absolute" />
        <div
          class="absolute text-white text-[16px] w-64.75 mt-74.25 ml-10 z-20"
        >
          User-friendly dashboard
          <p class="text-white/70">
            Perform complex SEO audits and optimizations with a single click.
          </p>
        </div>
      </div>
    </div>
    <div class="flex gap-2.5 mt-7.75">
      <div
        data-aos="fade-right"
        data-aos-delay="1000"
        data-aos-duration="1000"
        class="flex flex-wrap w-186 h-100 shadow-[inset_0_-220px_260px_-80px_rgba(54,23,100,1)]"
      >
        <Game class="ml-auto mt-auto" />
        <Purple class="absolute" />
        <div
          class="absolute text-white text-[16px] w-64.75 mt-74.25 ml-10 z-20"
        >
          User-friendly dashboard
          <p class="text-white/70">
            Perform complex SEO audits and optimizations with a single click.
          </p>
        </div>
      </div>
      <div
        data-aos="fade-left"
        data-aos-delay="1100"
        data-aos-duration="1000"
        class="flex flex-wrap items-center justify-center w-86.5 h-100 border-white/15 rounded-xl border"
      >
        <Triangle />
        <div class="text-white text-[16px] w-64.75">
          Smart Keyword Generator
          <p class="text-white/70">
            Automatic suggestions and the best keywords to target.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
