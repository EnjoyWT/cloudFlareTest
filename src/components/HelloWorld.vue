<!--
 * @Author: JoyWT
 * @Date: 2021-05-14 10:52:48
 * @LastEditors: JoyWT
 * @LastEditTime: 2021-05-14 11:09:22
 * @version: 1.0
 * @Description: 
-->
<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
