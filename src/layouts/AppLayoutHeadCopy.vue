<template>
  <VHeader></VHeader>
  <main>
    <slot />
  </main>
  <juancarlosperezCopy />
</template>

<script setup>
import SvgSprite from "../components/SvgSprite.vue";
import VHeader from "../base/VHeader.vue";
import juancarlosperez from "../components/juancarlosperez.vue";
</script>
