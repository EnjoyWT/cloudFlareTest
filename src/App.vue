<template>
  <div id="app">
    <img alt="Vue logo" src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.caixin.com%2F2020-03-28%2F1585373533147178_480_320.jpg&refer=http%3A%2F%2Fimg.caixin.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1623553869&t=ca2bcf1fdb012e848849d28bc8c17b3d">
    <HelloWorld msg="Are you serious!!"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
