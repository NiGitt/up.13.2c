<script setup>
import {RouterView } from 'vue-router'
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "@/components/TheFooter.vue";
import MainPage from "@/pages/MainPage.vue";
</script>

<template>
  <TheHeader />

  <MainPage />
  <TheFooter />
  <RouterView />
</template>

<style scoped>

</style>
