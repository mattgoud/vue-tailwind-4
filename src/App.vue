<template>
  <header class="flex flex-col gap-y-4 p-5 bg-gray-100">
    <nav class="flex gap-x-4">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>
  <main class="flex flex-col gap-y-4 p-5!">
    <RouterView />
  </main>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<style></style>
