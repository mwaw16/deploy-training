<template>
  <div class="wrapper">
    <h1>Deploy training</h1>
    <div class="color-wrapper">
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
      <dpl-color></dpl-color>
    </div>
  </div>
</template>

<script setup>
import dplColor from "./components/dplColor.vue";
</script>

<style scoped>
.wrapper {
  padding: 100px;
}

h1 {
  text-align: center;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  color: purple;
  margin-bottom: 50px;
}

.color-wrapper {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
</style>
