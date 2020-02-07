<template>
  <div class="searchCenter">
    <el-row>
      <el-col>
        <div class="searchUp">
          <div class="div1">宝贝</div>
          <div class="div2">天猫</div>
          <div class="div3">店铺</div>
          <i class="fa fa-camera" aria-hidden="true"></i>
        </div>
      </el-col>
      <el-col>
        <div class="searchButtonDiv">
          <button class="searchButton">搜索</button>
        </div>
        <div class="searchWrap">
          <i class="fa fa-search" aria-hidden="true"></i>
          <input type="text" placeholder="        多功能缝纫机" class="searchInput" />
        </div>
      </el-col>
      <el-col>
        <div class="searchDown">
          <span>
            <nuxt-link to="aaa">新款连衣裙</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">四件套</nuxt-link>
          </span>
          <span>
            <nuxt-link class="orange" to="aaa">潮流t恤</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">时尚女鞋</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">短裤</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">半身裙</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">男士外套</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">墙纸</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">行车记录仪</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">新款男鞋</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">耳机</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">时尚女包</nuxt-link>
          </span>
          <span>
            <nuxt-link to="aaa">沙发</nuxt-link>
          </span>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script lang="scss">
@import '../../../assets/css/public/header/searchCenter.scss';
</script>