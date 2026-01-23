<script setup>
import Blur from "../assets/Blur.vue";
import MainPage from "../assets/MainPage.vue";

const emit = defineEmits({
  downloadSoft(payload) {
    console.log(`Валидация ${payload ? true : false}`);
    return payload;
  },
});

function call() {
  emit("downloadSoft", "Загружаем");
}
</script>

<template>
  <div
    class="w-full border border-t-white/15 grid justify-items-center overflow-x-hidden"
  >
    <div
      class="inline-flex border border-white/15 gap-2 px-4 py-2 rounded-[50px] mt-22.5 mb-3.5"
      data-aos="fade-up"
      data-aos-duration="1000"
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
    <div
      class="w-146.5 grid justify-items-center z-30"
      data-aos="fade-up"
      data-aos-delay="200"
      data-aos-duration="1000"
    >
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
        <button class="bg-white px-4 py-2 rounded-lg z-30" @click="call()">
          Download
        </button>
      </div>
    </div>
    <div
      class="relative overflow-hidden w-280 h-160 bg-white/10 rounded-[30px] flex justify-center inset-0 shadow-[0_-120px_1500px_rgba(140,69,255,.90)] z-0"
      data-aos="fade-up"
      data-aos-anchor-placement="top-bottom"
      data-aos-delay="500"
      data-aos-duration="1000"
    >
      <MainPage class="relative z-0 max-h-full overflow-y-hidden" />
    </div>
  </div>
</template>
