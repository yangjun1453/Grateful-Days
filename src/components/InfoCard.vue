<template>
  <div class="box">
    <img src="" alt="">
    <div class="text"><h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil id molestiae</h3>

      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil id molestiae </p></div>

    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
         class="size-6">
      <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"/>


    </svg>

  </div>

</template>
<script setup name="InfoCard">

</script>
<style scoped>
.box {
  border-bottom: 3px solid white;
  display: flex;
  padding: 25px 10px;
  gap: 30px;
  line-height: 2;

}
.box:hover{
  background-color: #dbe4ff;
}

.box h3 {
  color: #b197fc
}

svg {
  width: 20px;
  height: auto;
  margin-left: auto;
}

</style>
