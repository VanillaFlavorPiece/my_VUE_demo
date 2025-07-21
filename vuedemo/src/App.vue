<template>
    <HelloWorld msg="此为模拟的导航栏"/>
  <img alt="首页 logo" src="./assets/doro.gif">

  <testCompo msg="此为测试VUE项目添加用"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import testCompo from './components/testCompo.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    testCompo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
