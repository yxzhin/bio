<script setup lang="ts">
import AvatarImage from "./components/AvatarImage.vue"
import HeadText from "./components/HeadText.vue"
</script>

<template>
  <div class="flex w-full justify-center p-16">
    <div
      class="max-w-2xl rounded-2xl bg-container shadow-xl p-8 text-center"
    >
      <AvatarImage></AvatarImage>
      <HeadText></HeadText>
    </div>
  </div>
</template>

<style>
body {
  background-color: var(--color-background);
}
</style>
