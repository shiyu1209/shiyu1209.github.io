<template>
    <div id="app">
        <div class="background-image"></div> <!-- 背景层 -->
        <div class="wave-background wave-layer1"></div> <!-- 波浪层1 -->
        <div class="wave-background wave-layer2"></div> <!-- 波浪层2 -->
        <div class="wave-background wave-layer3"></div> <!-- 波浪层3 -->
        <div class="wave-background wave-layer4"></div> <!-- 波浪层4 -->
    </div>
</template>

<script>
export default {
    name: 'WaveBackground' // 修改组件名称为多词名称
};
</script>

<style>
:root {
    --wave-height: 100px; /* 设置波浪高度 */
}

.background-image {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('/public/image/cat.jpg'); /* 确保路径正确，引用 public 文件夹中的资源 */
    background-size: cover;
    background-position: center;
    z-index: -2; /* 确保在波浪层下方 */
}
</style>