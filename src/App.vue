<script setup>
import Navigation from "./components/Navigation.vue";
import Hero from "./components/Hero.vue";
import Companies from "./components/Companies.vue";
import Bento from "./components/Bento.vue";
import Features from "./components/Features.vue";

function download(file) {
  console.log(file);
}
</script>

<template class="scroll-smooth">
  <Navigation />
  <Hero @download-soft="download" />
  <Companies />
  <Bento />
  <Features />
</template>

<style scoped></style>
