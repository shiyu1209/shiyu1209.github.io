<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Welcome to your Vue.js app!</p>
  </div>
</template>

<script>
// 这里添加你的 Vue 组件逻辑
</script>

<style scoped>
.hello {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* 占满整个视口高度 */
  flex-direction: column; /* 垂直排列内容 */
}

h1 {
  text-align: center;
}
</style>