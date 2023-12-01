<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
import Navigation from "./components/Navigation.vue";
</script>

<template>
  <header class="primary-header">
    <Navigation />
  </header>

  <RouterView />
</template>

<style scoped></style>
