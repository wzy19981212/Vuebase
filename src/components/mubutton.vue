<template>
  <div>
    <h1>我爱刘亦菲</h1>
    <button @click="count++">爱了{{ count }}次</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<style lang="less" scoped>
</style>
