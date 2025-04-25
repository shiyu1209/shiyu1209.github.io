<template>
  <div class="logo-container">
    <img alt="Vue logo" src="../../public/image/logo.png" /> 
  </div>
</template>

<script>
export default {
  name: 'LogoAndButtons'
};
</script>

<style>
.logo-container {
  position: absolute;
  top: 30px; /* 调整为左上角 */
  left: 30px; /* 调整为左上角 */
  background-color: rgba(255, 255, 255, 0.5); /* 半透明背景 */
  padding: 10px; /* 调整内边距 */
  border-radius: 10px; /* 圆角 */
  cursor: pointer;
  display: inline-flex;
  align-items: center;
}

.logo-container img {
  width: 100px;
  height: 50px;
  display: block; /* 新增显示属性确保图片可见 */
}
</style>
