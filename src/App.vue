<script setup>
import { RouterView } from 'vue-router'
import PageHeader from './components/PageHeader.vue'
import PageFooter from './components/PageFooter.vue'
</script>

<template>
  <div class="flex flex-col h-screen">
    <div class="py-8">
      <PageHeader />
    </div>
    <RouterView class="mb-auto" />
    <div class="py-8">
      <PageFooter />
    </div>
  </div>
</template>

<style scoped></style>
