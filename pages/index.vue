<template>
  <div class="totalHigh">
    <el-row class="totalHigh">
      <el-col class="mainUper">
        <main-uper/>
      </el-col>
      <el-col>2<span class="iconfont" style="font-size:22px;color:green;">&#xe727;</span></el-col>
      <el-col>3</el-col>
    </el-row>
  </div>
</template>

<script>
import MainUper from '../components/public/main/mainUper'
export default {
  components: {
    MainUper
  }
}
</script>

<style>

</style>
