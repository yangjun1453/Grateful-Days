<script setup>

import One from "./components/ProfileInfo.vue";
import Two from "./components/SkillList.vue";
import Three from "./components/PhotoList.vue";
import Box from "./components/InfoCard.vue";
</script>

<template>


  <div class="main">

    <div class="left">
      <One/>
      <Two/>

    </div>
    <div class="right">
      <Three/>


    </div>
  </div>
</template>

<style scoped>
.main {
  display: flex;

}

.left {

  display: flex;
  flex-direction: column;
  width: 300px;


}

.right {
  margin-left: 50px;
}
</style>
