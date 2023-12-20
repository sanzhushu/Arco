<script setup>
import { ref, onMounted } from "vue";
const count = ref(0);
onMounted(() => {
  console.log(count.value);
});
</script>
<template>
  <div class="wrapper">12121212</div>
</template>
<style scoped lang="less">
.wrapper {
  width: 100px;
  height: 100px;
  background-color: red;
  font-size: 120px;
}
</style>
