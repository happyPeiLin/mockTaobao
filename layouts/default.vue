<template>
  <div class="layout-blank">
    <el-container>
      <el-header class="el-headerT">
        <my-header />
      </el-header>
      <el-main>
        <nuxt/>
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>

<script>
import MyHeader from "@/components/public/header/index";
export default {
  components: {
    MyHeader
  }
};
</script>

<style lang="scss">
@import "@/assets/css/public/layout.scss";
</style>

