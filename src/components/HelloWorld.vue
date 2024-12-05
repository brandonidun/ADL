
<template>
  <div class="bg-blue-500 text-white text-center p-4 rounded-md shadow-lg">
    <h1 class="text-2xl font-bold">Hello, Tailwind!</h1>
    <p class="mt-2 text-lg">If you see this styled, Tailwind is working!</p>
  </div>
</template>
<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>

<style scoped>
</style>
