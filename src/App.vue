<template>
  <div id="app">
    <LogoAndButtons /> <!-- 引入 Logo 和按钮组件 -->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <WaveBackground /> <!-- 更新组件名称 -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import WaveBackground from './components/bolang.vue';
import LogoAndButtons from './components/Logo and buttons.vue'; // 引入 Logo 和按钮组件

export default {
  name: 'App',
  components: {
    HelloWorld,
    WaveBackground,
    LogoAndButtons // 注册组件
  },
  methods: {
    goToHome() {
      console.log('返回主页面');
    }
  }
}
</script>

