<script setup>
import { ref } from "vue";

const currentDate = ref(new Date().toLocaleString("ru-Ru"));
</script>

<template>
  <div :class="app">
    <h1>Дата:</h1>
    <p>{{ currentDate }}</p>
  </div>
</template>

<style scoped>
.app {
  padding: 20px;
}

h1 {
  margin-bottom: 8px;
  font-size: 20px;
}

p {
  font-size: 16px;
}
</style>
