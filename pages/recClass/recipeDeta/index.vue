<template>
  <div class="wk">
    <el-breadcrumb separator-class="el-icon-arrow-right">
      <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>日式</el-breadcrumb-item>
      <el-breadcrumb-item>草莓奶冻——日本超人气小食（不用琼脂版本）【健康小食】 </el-breadcrumb-item>
    </el-breadcrumb>
    <div class="reci">
      <h2>草莓奶冻——日本超人气小食（不用琼脂版本）【健康小食】<span>独家</span></h2>
      <el-row>
        <el-col :span="8">
          <el-card  :body-style="{ padding: '0px' }">
            <img src="../../../static/xxcp/18.jpg" class="image">
            <div style="padding: 14px;">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
              <el-button type="primary">收藏</el-button>
            </div>
          </el-card>
        </el-col>
      </el-row>
    </div>
    <div class="reqi"></div>
  </div>
</template>

<script>
  export default {}
</script>

<style scoped>
  .wk{
    width: 1000px;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 50px;
  }
  .reci{
    width: 65%;
    overflow: hidden;
  }
  .reci /deep/ .el-col-8{
    width: 100%;
  }
  .reci /deep/ .el-col-8 img{
    width: 100%;
  }
</style>
