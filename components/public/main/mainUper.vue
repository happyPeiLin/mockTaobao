<template>
  <el-row class="totalHigh">
    <el-col class="totalHigh mainUperCol1" :span="8">b1</el-col>
    <el-col class="totalHigh mainUperCol2" :span="8">
      <h2>主题市场</h2>
    </el-col>
    <el-col class="totalHigh mainUperCol3" :span="8">
        <ul class="forUl totalHigh">
            <li id="head"> <nuxt-link to="#" style="color:#ffffff">天猫</nuxt-link></li>
            <li> <nuxt-link to="#" style="color:#ffffff">聚划算</nuxt-link><span class="iconfont nick" style="font-size:22px;">&#xe727;</span></li>
            <li> <nuxt-link to="#" style="color:#ffffff">天猫超市</nuxt-link></li>
        </ul>
        <ul class="forUl totalHigh">
            <li>|</li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">淘抢购</nuxt-link></li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">电器城</nuxt-link></li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">司法拍卖</nuxt-link></li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">淘宝心选</nuxt-link></li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">兴农脱贫</nuxt-link></li>
        </ul>
        <ul class="forUl totalHigh">
            <li>|</li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">飞猪旅行</nuxt-link></li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">智能生活</nuxt-link></li>
            <li><nuxt-link to="#" style="color:#ffffff;font-size:14px">苏宁易购</nuxt-link></li>
        </ul>
    </el-col>
  </el-row>
</template>

<style lang="scss">
@import "@/assets/css/public/main/mainUper.scss";
</style>