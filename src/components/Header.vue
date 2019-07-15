<template>
  <div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">
    <header class="mdl-layout__header">
      <div class="mdl-layout__header-row">
        <i class="material-icons">dehaze</i><br>
        <span class="mdl-layout-title">Vue practice</span>
        <br>
        <el-button type="primary" icon="el-icon-edit"></el-button>
        <el-button type="success" icon="el-icon-check"></el-button>
        <el-button type="info" icon="el-icon-message"></el-button>
        <el-button type="warning" icon="el-icon-star-off"></el-button>
        <el-button type="danger" icon="el-icon-delete"></el-button>
        <ButtonGroup/>
      </div>
    </header>
  </div>
</template>

<script lang="ts">
  import {Component, Prop, Vue} from 'vue-property-decorator';

</script>
<style scoped>
.mdl-layout__header-row {
  padding: 0 16px;
}
i {
  padding-right: 16px;
}
</style>
