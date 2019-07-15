<template>
  <div id="app">
    <Header/>
    <ButtonGroup/>
  </div>
</template>

<script>
// ./componentsに配置したコンポーネント(.vueファイル)をimportする
// 赤字のところが上のtemplateタグ内で呼び出すnameになる
  import Header from './components/Header.vue'
  import Hello from './components/HelloWorld.vue'
  import ButtonGroup from './components/ButtonGroup.vue'

// ここでエクスポートする
  export default {
    components: {
      Header
    , Hello
    , ButtonGroup
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
  margin-top: 0px;
}
</style>
