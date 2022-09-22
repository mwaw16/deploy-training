<template>
  <div @click="setColor" :style="dupa" class="dpl-color"></div>
</template>

<script setup>
import { ref } from "vue";

const dupa = ref("");

function setColor() {
  dupa.value = `background-color: #${Math.floor(
    Math.random() * 16777215
  ).toString(16)};`;
}
</script>

<style>
.dpl-color {
  width: 60px;
  height: 60px;
  background-color: lightgray;
  border-radius: 5px;
  transition: background-color 0.3s ease-in-out;
  cursor: pointer;
}
</style>
