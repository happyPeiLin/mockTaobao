<template>
  <div class="totalHigh">
    <el-row>
      <header/>
    </el-row>
    <el-row class="totalHigh">
      <el-col class="mainUper">
        <main-uper/>
      </el-col>
      <el-row>
        <el-col id="center1" :span="4">1</el-col>
        <el-col id="center2" :span="12">2</el-col>
        <el-col id="center3" :span="4">3</el-col>
      </el-row>
    </el-row>
  </div>
</template>

<script>
import Header from '../components/public/header/index'
import MainUper from '../components/public/main/mainUper'
export default {
  components: {
    MainUper,
    Header
  }
}
</script>

<style lang="scss" scoped>
  @import '@/assets/css/public/main/mainCenter.scss';
</style>

