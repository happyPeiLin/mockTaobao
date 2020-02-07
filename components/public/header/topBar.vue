<template>
  <div class="topbar">
    <el-row class="topbarRow" :gutter="0">
      <el-col class="topbarRow" :span="12">
        <top-left/>
      </el-col>
      <el-col class="topbarRow" :span="12">
        <top-right/>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import TopLeft from './topLeft'
import topRight from './topRight'
export default {
  components:{
    TopLeft,
    topRight
  }
}
</script>