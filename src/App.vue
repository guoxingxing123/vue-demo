<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
     <p>我是project分支修改的</p>
    <p>我是dev分支修改的</p>
     <p>我要开始尝试使用git stash了</p>
  </div>
</template>

<script>
export default {
  name: 'App'
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
