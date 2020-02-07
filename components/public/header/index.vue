<template>
  <div>
    <el-row>
      <el-col>
        <topbar />
      </el-col>
      <el-col>
        <search />
      </el-col>
    </el-row>
  </div>
</template>

<script>
import Topbar from "./topBar";
import Search from "./search";
export default {
  components: {
    Topbar,
    Search
  }
};
</script>