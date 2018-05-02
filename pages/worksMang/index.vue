<template>
  <div class="wk">
    <div class="useIn">
      <div class="tx fl">
        <img src="../../static/xxcp/18.png" alt="">
      </div>
      <div class="useNname fl">
        <h2>手机用户6857_pofd的厨房</h2>
        <span>2018-04-01 加入</span>
      </div>
      <div class="shezhi fl">
        <span>设置个人信息</span>
        <ul>
          <li class="fl">
            关注的人
            <p>13</p>
          </li>
          <li class="fl">
            被关注
            <p>1</p>
          </li>
        </ul>
      </div>
      <div class="zpList">
        <ul>
          <li>概况</li>
          <li>菜谱</li>
          <li>作品</li>
          <li>菜单</li>
          <li>留言板</li>
          <li>草稿箱</li>
          <li>收藏</li>
        </ul>
      </div>
      <div class="ms">
        <h3>夜观天象，传说一只未来大厨将从这里启程...</h3>
        <p>找到你会做的菜，传上你的作品</p>
        <p>找不到？你可以创建菜谱，亮出你的独门绝技</p>
        <el-input placeholder="搜索菜谱、食谱" v-model="input5" class="input-with-select">
          <el-button slot="append" icon="el-icon-search"></el-button>
        </el-input>
      </div>
    </div>
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
  .useIn .tx{
    overflow: hidden;
  }
  .useIn .tx img{
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
  .useIn .useNname {
    margin-left: 50px;
    overflow: hidden;
  }
  .useIn .useNname h2{
    margin: 0 0 16px;
    font-weight: 700;
    font-size: 34px;
  }
  .useIn .useNname span{
    margin-top: -30px;
    color: #7f828b;
    font-size: 12px;
  }
  .shezhi{
    width: 200px;
    height: 200px;
    margin-left: 50px;
    position: relative;
    overflow: hidden;
  }
  .shezhi span{
    font-size: 12px;
    color: #7f828b;
    position: absolute;
    top: 10px;
    right: 10px;
  }
  .shezhi ul{
    position: absolute;
    bottom: 10px;
    right: 10px;
  }
  .shezhi ul li{
    padding: 10px;
    background-color: #f5f6f5;
    color: #333;
    text-align: center;
  }
  .shezhi ul li:first-child{
    border-right: 1px solid #7f828b;
  }
  .shezhi ul li p{
    color: #dd3915;
    font-weight: 600;
  }
  .zpList{
    width: 100%;
    margin-top: 20px;
    float: left;
  }
  .zpList ul{
    width: 100%;
    height: 40px;
    background-color: #f5f6f5;
  }
  .zpList ul li{
    width: 100px;
    float: left;
    line-height: 40px;
    text-align: center;
    border-right: 1px solid #fff;
  }
  .ms{
    float: left;
    width: 400px;
    margin: 60px 300px;
    text-align: center;
  }
  .ms h3{
    font-size: 20px;
    font-weight: 600;
    line-height: 2.8;
  }
  .ms p{
    margin-bottom: 15px;
  }
</style>
