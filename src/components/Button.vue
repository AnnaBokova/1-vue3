<script setup></script>

<template>
  <button class="button">Кнопка</button>
</template>

<style scoped>
.button {
  font-family: var(--font);
  color: var(--color-text-button);
  background: var(--color-primary);
  font-weight: 400;
  font-size: 24px;
  line-height: 150%;
  text-align: center;
  border: none;
  border-radius: 100px;
  padding: 16px 10px;
  width: 335px;
  height: 68px;
  cursor: pointer;
}
.button:hover {
  background: var(--color-button-hover);
}
</style>
