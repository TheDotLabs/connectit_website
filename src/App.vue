<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
import AppBar from "./components/AppBar.vue";
import Body from "./components/Body.vue";
</script>

<template>
  <div class="h-screen w-screen">
    <AppBar class="absolute top-0" />
    <Body class="h-screen overflow-y-auto pt-16 no-scrollbar" />
  </div>
</template>
