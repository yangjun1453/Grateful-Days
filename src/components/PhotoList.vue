<template>
  <h1>
    My photo lists
  </h1>
  <div class="main">
    <box/>

    <box/>

    <box/>
    <box/>
  </div>
</template>

<script setup name="PhotoList">
import Box from "./InfoCard.vue";
</script>

<style scoped>
.main {
  display: flex;
  flex-direction: column;
  padding: 13px;
  gap: 15px;
  margin-bottom: 30px;
  border-radius: 7px;
  background-color: #f8f9fa;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08);


}
</style>
