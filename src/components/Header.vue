<template>
  <div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">
    <header class="mdl-layout__header">
      <div class="mdl-layout__header-row">
        <i class="material-icons">dehaze</i>
        <h1>{{ miss }}</h1>
        <span class="mdl-layout-title">GIPHY-VUE</span>
        <br>
        <el-button type="primary" icon="el-icon-edit"></el-button>
        <el-button type="success" icon="el-icon-check"></el-button>
        <el-button type="info" icon="el-icon-message"></el-button>
        <el-button type="warning" icon="el-icon-star-off"></el-button>
        <el-button type="danger" icon="el-icon-delete"></el-button><br><br>
      <el-button-group>
        <el-button type="primary" icon="el-icon-message"></el-button>
        <el-button type="primary" icon="el-icon-star-off"></el-button>
        <el-button type="primary" icon="el-icon-delete"></el-button>
      </el-button-group>
      </div>
    </header>
  </div>
</template>

<script lang="ts">
  import {Component, Prop, Vue} from 'vue-property-decorator';

  Component
  export default class HeaderVue extends Vue {
    @Prop() private miss!: string;
  }
</script>
<style scoped>
.mdl-layout__header-row {
  padding: 0 16px;
}
i {
  padding-right: 16px;
}
</style>
