<template>
  <div class="wk">
    <el-breadcrumb separator-class="el-icon-arrow-right">
      <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>日式</el-breadcrumb-item>
      <el-breadcrumb-item>草莓奶冻——日本超人气小食（不用琼脂版本）【健康小食】 </el-breadcrumb-item>
    </el-breadcrumb>
    <div class="reci fl">
      <h2 class="timu">草莓奶冻——日本超人气小食（不用琼脂版本）【健康小食】<span>独家</span></h2>
      <el-row>
        <el-col :span="8">
          <el-card  :body-style="{ padding: '0px' }">
            <div class="imghewi">
              <img src="../../../static/xxcp/18.jpg" class="image">
            </div>
            <div style="padding: 14px;" class="pingfen">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
              <el-button type="primary" class="fr sc">收藏</el-button>
            </div>
          </el-card>
        </el-col>
      </el-row>
      <div class="buzhou">
        <div class="zhizuoren">
          <div class="fl">
            <img src="../../../static/xxcp/19.jpg" alt="">
          </div>
          <span class="fl">Sunsun</span>
        </div>
        <div class="guocheng">
          <div class="miaoshu">
            <h3>日本的超人气草莓羊羹啊，家里只有这些也一样做，用吉利丁片代替琼脂了，口感是软化的，但是颜值真的不是盖的。</h3>
          </div>
          <div class="yongliao">
            <h2>用料</h2>
            <ul>
              <li>
                <span>淡奶油</span>
                <span>200ml</span>
              </li>
              <li>
                <span>淡奶油</span>
                <span>200ml</span>
              </li>
              <li>
                <span>淡奶油</span>
                <span>200ml</span>
              </li>
              <li>
                <span>淡奶油</span>
                <span>200ml</span>
              </li>
              <li>
                <span>淡奶油</span>
                <span>200ml</span>
              </li>
            </ul>
          </div>
          <div class="xq">
            <h2>草莓奶冻——日本超人气小食（不用琼脂版本）【健康小食】的做法 </h2>
            <ul>
              <li>
                <i>1</i>
                <span>倒入模具中（用乐扣的饭盒就OK，最好是能没过草莓的量）常温下冷却半小时，把洗干净的草莓放到磨具里，手指轻摁，埋到奶冻中，然后放入冷藏中4小时即可。</span>
              </li>
              <li>
                <i>1</i>
                <span>吉利丁片用冷水泡软。（一定要用冷水，否则易溶化）</span>
              </li>
              <li>
                <i>1</i>
                <span>吉利丁片用冷水泡软。（一定要用冷水，否则易溶化）</span>
              </li>
              <li>
                <i>1</i>
                <span>吉利丁片用冷水泡软。（一定要用冷水，否则易溶化）</span>
              </li>
            </ul>
          </div>
          <div class="xiaotieshi">
            <h4>小贴士</h4>
            <p>用塑料盒热敷法装很好脱模，不用担心会坑坑洼洼</p>
            <p>糖量我是根据自己不适甜的口味加的。所以婊贝们喜欢甜口可以多加10g</p>
          </div>
        </div>
      </div>
    </div>
    <div class="reqi fl">
      <h2>被大家加入到以下菜单</h2>
      <el-row>
        <el-col :span="8">
          <el-card  :body-style="{ padding: '0px' }">
            <div class="imghewi">
              <img src="../../../static/xxcp/08.jpg" class="image">
            </div>
            <div style="padding: 14px;" class="pingfen">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
            </div>
          </el-card>
          <el-card  :body-style="{ padding: '0px' }">
            <div class="imghewi">
              <img src="../../../static/xxcp/08.jpg" class="image">
            </div>
            <div style="padding: 14px;" class="pingfen">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
            </div>
          </el-card>
          <el-card  :body-style="{ padding: '0px' }">
            <div class="imghewi">
              <img src="../../../static/xxcp/08.jpg" class="image">
            </div>
            <div style="padding: 14px;" class="pingfen">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
            </div>
          </el-card>
          <el-card  :body-style="{ padding: '0px' }">
            <div class="imghewi">
              <img src="../../../static/xxcp/08.jpg" class="image">
            </div>
            <div style="padding: 14px;" class="pingfen">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
            </div>
          </el-card>
          <el-card  :body-style="{ padding: '0px' }">
            <div class="imghewi">
              <img src="../../../static/xxcp/08.jpg" class="image">
            </div>
            <div style="padding: 14px;" class="pingfen">
              <span><i>7.7</i>综合评分&nbsp;&nbsp;<i>54</i>人做过这道菜</span>
            </div>
          </el-card>
        </el-col>
      </el-row>
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
  .reci{
    width: 65%;
    overflow: hidden;
  }
  .reci /deep/ .el-col-8{
    width: 100%;
  }
  .timu{
    font-size: 34px;
    font-weight: 700;
    margin-top: 15px;
  }
  .reci .imghewi{
    width: 100%;
    height: 400px;
    overflow: hidden;
  }
  .reci /deep/ .el-col-8 img{
    width: 100%;
    margin-top: -300px;
  }
  .reci .pingfen span i{
    font-size: 20px;
    color: #dd3915;
    vertical-align: middle;
    font-weight: 700;
    margin-right: 15px;
  }
  .reci .sc{
    margin-bottom: 10px;
  }
  .buzhou{
    margin-top: 30px;
  }
  .zhizuoren{
    width: 100%;
    overflow: hidden;
  }
  .zhizuoren img{
    width: 40px;
    height: 40px;
    border-radius: 50%;
    margin-right: 20px;
  }
  .zhizuoren span{
    margin-top: 10px;
  }
  .guocheng, .xq, .xiaotieshi{
    width: 100%;
    overflow: hidden;
  }
  .guocheng h2,
  .reqi h2{
    color: #c0ae7d;
    margin-bottom: 10px;
    font-size: 24px;
    font-weight: 700
  }
  .guocheng .miaoshu h3{
    font-size: 18px;
    margin-top: 30px;
    margin-bottom: 16px;
  }
  .yongliao li{
    border-bottom: 1px solid #f0f0f0;
    padding: 5px 0;
    width: 100%;
    font-size: 18px;
  }
  .yongliao li span{
    display: inline-block;
  }
  .yongliao li span:first-child{
    margin-right: 200px;
  }
  .xq li{
    width: 100%;
    margin-bottom: 20px;
    font-size: 18px;
  }
  .xq li i{
    display: inline-block;
    color: #c0ae7d;
    font-size: 24px;
    font-weight: 700;
    margin-right: 15px;
  }
  .xiaotieshi{
    width: 100%;
    min-height: 100px;
    background-color: #f5f6f5;
    padding: 32px;
    font-size: 16px;
    color: #222;
    margin-top: 30px;
  }
  .xiaotieshi h4{
    margin-bottom: 15px;
    font-weight: 600;
  }
  .reqi{
    width: 30%;
    margin-left: 5%;
  }
  .reqi /deep/ .el-col-8,
  .reqi /deep/ .el-col-8 img{
    width: 100%;
  }
  .reqi /deep/ .el-card{
    margin-bottom: 30px;
  }
</style>
