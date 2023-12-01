<script setup>
import {ref } from "vue";
import MainPage from "../components/MainPage.vue";
import About from "../components/About.vue";
import { onMounted } from "vue";


const authorName = ref();

onMounted(() => {
  authorName.value = "André";
});
</script>

<template>
  <main>
    <section>
      <MainPage />
    </section>
    <section>
      <About :author="authorName" />
    </section>
  </main>
</template>
