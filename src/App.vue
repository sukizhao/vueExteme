<template>
  <!-- vue的模板里面 所有的内容要被一个根节点包含起来  -->
  <div id="app">
    <v-home></v-home>
  </div>
</template>

<script>
import Home from "./components/Home.vue"; //1、引入组建
export default {
  data() {
    /*业务逻辑里面定义的数据*/
    return {};
  },
  // 2、挂载组建  3、在app.vue里面使用模块
  components: {
    "v-home": Home
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
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
