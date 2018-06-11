<template>
  <div id="app">
    <el-row :gutter="10">
      <el-col :xs="20" :lg="4"><Nav /></el-col>
      <el-col :xs="20" :lg="4"><router-view/></el-col>
    </el-row>
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue";
export default {
  name: 'App',
  components: { Nav }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
