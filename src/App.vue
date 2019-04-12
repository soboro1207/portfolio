<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <Header/>
    <!-- <HelloWorld/> -->
    <!-- <router-view/> -->
  </div>
</template>

<script>
// ./componentsに配置したコンポーネント(.vueファイル)をimportする
// 赤字のところがtemplateタグ内で呼び出すタグ名になる、だいたい同じにしておく
  import Header from './components/Header.vue'
//  import HelloWorld from './components/HelloWorld.vue'

// ここに書く
  export default {
    components: {
      Header
//      HelloWorld
    }
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
