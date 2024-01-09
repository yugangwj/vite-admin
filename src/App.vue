<template>
  <el-row class="mb-4 bg">
    <el-button>Default</el-button>
    <el-button type="primary">Primary</el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
  </el-row>
  <i-ep-add-location />

  <i-ep-add-location />
  <i-ep-aim />
</template>

<script setup lang="ts">
// import { ref, reactive } from "vue";
</script>

<style lang="scss" scoped>
.bg {
  width: 500px;
  height: 500px;
  background-color: $bg-color;
}
</style>
