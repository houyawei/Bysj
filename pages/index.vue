<template>
  <section class="container">
    <div class="main">
      <div class="list fl">
        <ul>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
          <li>
            <i class="iconfont icon-jidan"></i>
            <span>家常菜</span>
          </li>
        </ul>
      </div>
      <!--轮播图与注册那块-->
      <div class="on-top fl">
        <!--轮播图-->
        <div class="map fl">
          <el-carousel indicator-position="outside">
            <el-carousel-item>
              <img src="../static/lunbo/01.jpg" alt="">
              <div class="alt">
                <span>家常菜~杏鲍菇烧牛肉粒</span>
                <i>12 人做过这道菜</i>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img src="../static/lunbo/02.jpg" alt="">
              <div class="alt">
                <span>家常菜~杏鲍菇烧牛肉粒</span>
                <i>12 人做过这道菜</i>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img src="../static/lunbo/03.jpg" alt="">
              <div class="alt">
                <span>家常菜~杏鲍菇烧牛肉粒</span>
                <i>12 人做过这道菜</i>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img src="../static/lunbo/04.jpg" alt="">
              <div class="alt">
                <span>家常菜~杏鲍菇烧牛肉粒</span>
                <i>12 人做过这道菜</i>
              </div>
            </el-carousel-item>
          </el-carousel>
        </div>
        <!--登陆注册-->
        <div class="login-xia fl">
          <div class="tx"></div>
          <h2>手机用户6857_pofd的厨房</h2>
          <p>
            <span><i>0</i>收藏</span>|
            <span><i>0</i>收藏</span>|
            <span><i>0</i>收藏</span>|
            <span style="color: #dd3915">草稿箱</span>
          </p>
          <div class="cjcp">创建菜谱</div>
          <h4>网上不良信息举报专区</h4>
        </div>
      </div>
      <!--新秀菜谱-->
      <div class="xxcp fl">
        <!--新秀菜谱--内部-->
        <div class="xxcp-nei">
          <div class="title">
            <h2>新秀菜谱</h2>
            <span>全部</span>
          </div>
          <el-carousel height="150px" trigger="click">
            <el-carousel-item>
              <div class="list fl">
                <img src="../static/xxcp/01.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list marLe fl">
                <img src="../static/xxcp/02.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list fl">
                <img src="../static/xxcp/03.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <div class="list fl">
                <img src="../static/xxcp/01.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list marLe fl">
                <img src="../static/xxcp/02.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list fl">
                <img src="../static/xxcp/03.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <div class="list fl">
                <img src="../static/xxcp/01.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list marLe fl">
                <img src="../static/xxcp/02.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list fl">
                <img src="../static/xxcp/03.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <div class="list fl">
                <img src="../static/xxcp/01.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list marLe fl">
                <img src="../static/xxcp/02.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
              <div class="list fl">
                <img src="../static/xxcp/03.jpg" alt="">
                <span>菠菜木耳汤——快</span>
              </div>
            </el-carousel-item>
          </el-carousel>
        </div>
        <!--最近流行-->
        <div class="zjlx">
          <div class="title">
            <h2>最近流行</h2>
            <span>全部</span>
          </div>
          <el-row>
            <el-col :span="8">
              <el-card class="fl" :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card class="fl"  :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/04.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
            </el-col>
          </el-row>
        </div>
        <!--厨房问答-->
        <div class="cfwd">
          <div class="title">
            <h2>厨房问答</h2>
            <span>全部</span>
            <span class="fr">发起话题</span>
          </div>
          <ul>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
            <li>
              <h4>怎么炒淮山不粘稠？<span class="fr">25参与</span></h4>
            </li>
          </ul>
        </div>
        <!--时令食材-->
        <div class="slsc">
          <div class="title">
            <h2>时令食材</h2>
            <span>全部</span>
          </div>
          <div class="sc-back">
            <ul>
              <li class="marle">
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li>
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li>
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li>
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li class="marRi">
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li  class="marle">
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li>
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li>
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li>
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
              <li class="marRi">
                <img src="../static/xxcp/05.jpg" alt="">
                <span>春笋</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <!--流行搜索-->
      <div class="lxsc fl">
        <div class="lxsc-nei">
          <div class="title">
            <h2>流行搜索</h2>
          </div>
          <ul>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅
              <i class="iconfont icon-jidan"></i>
            </li>
            <li class="fl">
              <span>1</span>
              可乐鸡翅

            </li>
          </ul>
        </div>
        <!--流行单品-->
        <div class="lxdp">
          <div class="title">
            <h2>流行单品</h2>
            <span>全部</span>
          </div>
          <el-row>
            <el-col :span="8">
              <el-card class="fl" :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/06.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
              <el-card class="fl" :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/06.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
              <el-card class="fl" :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/06.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
              <el-card class="fl" :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/06.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
              <el-card class="fl" :body-style="{ padding: '0px' }">
                <img src="../static/xxcp/06.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
            </el-col>
          </el-row>
        </div>
        <!--下厨房的厨友们-->
        <div class="xcfdcym">
          <div class="title">
            <h2>下厨房的厨友们</h2>
            <span>更多</span>
          </div>
          <ul>
            <li>
              <img src="../static/xxcp/07.jpg" alt="" class="fl">
              <div class="info fl">
                <h5>花小麻dudu</h5>
                <h6>653 关注</h6>
                <h6>10 个菜谱  681 个作品</h6>
              </div>
              <div class="fl guanzhu">
                关注
              </div>
            </li>
            <li>
              <img src="../static/xxcp/07.jpg" alt="" class="fl">
              <div class="info fl">
                <h5>花小麻dudu</h5>
                <h6>653 关注</h6>
                <h6>10 个菜谱  681 个作品</h6>
              </div>
              <div class="fl guanzhu">
                关注
              </div>
            </li>
            <li>
              <img src="../static/xxcp/07.jpg" alt="" class="fl">
              <div class="info fl">
                <h5>花小麻dudu</h5>
                <h6>653 关注</h6>
                <h6>10 个菜谱  681 个作品</h6>
              </div>
              <div class="fl guanzhu">
                关注
              </div>
            </li>
            <li>
              <img src="../static/xxcp/07.jpg" alt="" class="fl">
              <div class="info fl">
                <h5>花小麻dudu</h5>
                <h6>653 关注</h6>
                <h6>10 个菜谱  681 个作品</h6>
              </div>
              <div class="fl guanzhu">
                关注
              </div>
            </li>
            <li>
              <img src="../static/xxcp/07.jpg" alt="" class="fl">
              <div class="info fl">
                <h5>花小麻dudu</h5>
                <h6>653 关注</h6>
                <h6>10 个菜谱  681 个作品</h6>
              </div>
              <div class="fl guanzhu">
                关注
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  components: {},
  data () {
    return {
      itemImg: [
        '../static/lunbo/01.jpg',
        '../static/lunbo/02.jpg',
        '../static/lunbo/03.jpg',
        '../static/lunbo/04.jpg',
      ]
    }
  }
}
</script>

<style>
  .main{
    margin-top: 100px;
  }
  .list li {
    margin-bottom: 15px;
  }
  .list li .iconfont{
    font-size: 20px;
  }
  .list li span{
    vertical-align: text-top;
    display: inline-block;
    margin-left: 10px;
    color: #222;
    font-size: 14px;
  }
  .on-top{
    margin-left: 50px;
    width: 82%;
  }
  .on-top .map{
    width: 55%;
    height: 280px;
  }
  .on-top .map img{
    width: 100%;
    height: 100%;
  }
  .map /deep/ .el-carousel-item{
    position: relative;
  }
  .map .alt{
    position: absolute;
    bottom: 30px;
    left: 15px;
    color: #fff;
  }
  .alt span{
    font-size: 30px;
    line-height: 1.4;
    margin-bottom: 0;
    font-weight: 700;
  }
  .alt i{
    display: block;
    font-size: 14px;
    margin-top: 5px;
    font-weight: 500;
  }
  .login-xia{
    position: relative;
    width: 37%;
    margin-left: 3%;
    background-color: #f5f6f5;
    height: 260px;
    text-align: center;
    padding: 30px 5px;
    margin-bottom: 30px;
    line-height: 1.2;
  }
  .login-xia .tx{
    width: 60px;
    height: 60px;
    margin: 0 auto;
    border-radius: 50%;
    background: url("../static/touxiang.png")no-repeat center;
    background-size: contain;
  }
  .login-xia h2{
    margin-top: 20px;
    overflow: hidden;
    color: #dd3915;
    text-decoration: none;
    font-size: 18px;
  }
  .login-xia p{
    margin-top: 20px;
    font-size: 12px;
  }
  .login-xia p span{
    display: inline-block;
    margin-right: 8px;
  }
  .login-xia .cjcp{
    width: 105px;
    height: 45px;
    line-height: 45px;
    color: #fff;
    background-color: #dd3915;
    margin: 20px auto;
  }
  .login-xia h4{
    color: #dd3915;
  }
  .xxcp{
    width: 45%;
    margin-left: 50px;
  }
  .xxcp .xxcp-nei{
    width: 100%;
    height: 150px;
  }
  .xxcp .title{
    width: 100%;
    margin-bottom: 15px;
  }
  .xxcp .title h2{
    display: inline-block;
    font-size: 20px;
    font-weight: 700;
    color: #c0ae7d;
  }
  .xxcp .title span{
    display: inline-block;
    color: #dd3915;
    font-size: 14px;
    margin-left: 20px;
  }
  .xxcp-nei{
    margin-bottom: 50px;
  }
  .xxcp-nei .list {
    width: 140px;
    height: 120px;
  }
  .xxcp-nei .list img{
    width: 140px;
  }
  .xxcp-nei .marLe{
    margin-left: 15px;
    margin-right: 15px;
  }
  .xxcp-nei .list span{
    display: block;
    overflow: hidden;
  }
  .xxcp-nei /deep/ .el-carousel__arrow{
    top: 35%;
  }
  .time {
    font-size: 13px;
    color: #999;
  }
  .bottom {
    margin-top: 13px;
    line-height: 12px;
  }
  .button {
    padding: 0;
    float: right;
  }
  .image {
    width: 100%;
    display: block;
  }
  .clearfix:before,
  .clearfix:after {
    display: table;
    content: "";
  }
  .clearfix:after {
    clear: both
  }
  .zjlx /deep/ .el-col-8{
    width: 100%;
  }
  .zjlx /deep/ .el-card{
    width: 48%;
  }
  .zjlx /deep/ .el-card:nth-child(2n){
    margin-left: 2%;
    margin-bottom: 5%;
  }
  .cfwd li{
    margin-bottom: 15px;
  }
  .cfwd li span{
    color: #909090;
    font-size: 12px;
  }
  .slsc .sc-back{
    background-color: #f5f6f5;
    margin: 0 -4px;
    padding: 0;
    min-width: 468px;
    overflow: hidden;
    padding: 15px 15px 7px;
  }
  .slsc .sc-back li{
    float: left;
    margin: 0 20px;
  }
  .slsc .sc-back .marle{
    margin-left: 0;
  }
  .slsc .sc-back .marRi{
    margin-right: 0;
  }
  .slsc .sc-back span{
    display: block;
    margin: 10px 0;
    text-align: center;
  }
  .lxsc{
    width: 30%;
    margin-left: 30px;
  }
  .lxsc .lxsc-nei{
    width: 100%;
    height: 150px;
  }
  .lxsc .title{
    width: 100%;
    margin-bottom: 15px;
  }
  .lxsc .title h2{
    display: inline-block;
    font-size: 20px;
    font-weight: 700;
    color: #c0ae7d;
  }
  .lxsc .title span{
    display: inline-block;
    color: #dd3915;
    font-size: 14px;
    margin-left: 20px;
  }
  .lxsc-nei li {
    float: left;
  }
  .lxsc-nei li:nth-child(2n){
    margin-left: 30px;
  }
  .lxsc-nei li span{
    display: inline-block;
    width: 18px;
    color: #909090;
    padding-right: 8px;
  }
  .lxdp{
    margin-top: 50px;
  }
  .lxdp .el-col-8{
    width: 100%;
  }
  .lxdp .el-col-8 .el-card{
    margin-bottom: 20px;
  }
  .xcfdcym{
    margin-top: 50px;
  }
  .xcfdcym li img{
    width: 70px;
    height: 70px;
    border-radius: 50%;
  }
  .xcfdcym .info h5{
    font-size: 14px;
    color: #333;
  }
  .xcfdcym .info h6{
    font-size: 14px;
    color: #999;
  }
  .xcfdcym li{
    width: 100%;
    height: 100px;
    overflow: hidden;
    border-bottom: solid 1px #7f828b;
    margin-bottom: 20px;
  }
  .xcfdcym li .guanzhu{
    width: 86px;
    height: 40px;
    line-height: 40px;
    color: #fff!important;
    background-color: #dd3915!important;
    text-align: center;
    margin-top: 10px;
  }
</style>
