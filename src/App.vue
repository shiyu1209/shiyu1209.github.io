<template>
  <div id="app">
    <LogoAndButtons />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <WaveBackground />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import WaveBackground from "./components/bolang.vue";
import LogoAndButtons from "./components/Logo and buttons.vue";


export default {
  name: "App",
  components: {
    HelloWorld,
    WaveBackground,
    LogoAndButtons,
  },
methods: {
    goToHome() {
      console.log('返回主页面');
    }
  }
}
</script>

