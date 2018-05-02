<template>
  <div class="homeCook">
    <div class="xiangqing">
      <!--标签-->
      <div class="biaoqian fl">
        <div>
          <ul>
            <li>全部分类</li>
            <li>本周最受欢迎</li>
            <li>新秀菜谱</li>
            <li>新秀菜谱</li>
            <li>新秀菜谱</li>
            <li>新秀菜谱</li>
            <li>新秀菜谱</li>
            <li>新秀菜谱</li>
          </ul>
          <div class="zhehe">
            <el-row class="tac">
              <el-col :span="12">
                <h5>默认颜色</h5>
                <el-menu
                  default-active="2"
                  class="el-menu-vertical-demo"
                  @open="handleOpen"
                  @close="handleClose">
                  <el-submenu index="1">
                    <template slot="title">
                      <i class="el-icon-location"></i>
                      <span>菜式</span>
                    </template>
                    <el-menu-item-group>
                      <template slot="title">特色食品</template>
                      <el-menu-item index="1-1">小吃</el-menu-item>
                      <el-menu-item index="1-2">沙拉</el-menu-item>
                    </el-menu-item-group>
                    <el-menu-item-group title="人群">
                      <el-menu-item index="1-3">儿童</el-menu-item>
                      <el-menu-item index="1-3">老人</el-menu-item>
                    </el-menu-item-group>
                    <el-submenu index="1-4">
                      <template slot="title">功效</template>
                      <el-menu-item index="1-4-1">减肥</el-menu-item>
                      <el-menu-item index="1-4-1">美容</el-menu-item>
                    </el-submenu>
                  </el-submenu>
                </el-menu>
              </el-col>
            </el-row>
          </div>
        </div>
      </div>
      <div class="zhucai fl">
        <h1>菜单</h1>
        <p><span>最近流行</span><i>|</i><span>最近创建</span></p>
        <ul>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
          <li>
            <img src="../../static/xxcp/11.jpg" alt="" class="fl">
            <div class="fl info">
              <h3>干锅土豆片<span>步骤图</span></h3>
              <p>土豆、豆瓣酱、葱花、盐、酱油、蒜顶顶顶</p>
              <h4>综合评分&nbsp;<span>7.6</span>（七天内 50 人做过</h4>
              <h6>妹子厨艺</h6>
            </div>
          </li>
        </ul>
        <el-pagination
          background
          layout="prev, pager, next"
          :total="1000">
        </el-pagination>
      </div>
      <div class="zuixin fl">
        <div class="xfcdqbcd">
          <h2>流行菜谱 <span>全部</span></h2>
          <el-row>
            <el-col :span="8">
              <el-card  :body-style="{ padding: '0px' }">
                <img src="../../static/xxcp/12.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <!--<time class="time"><span></span></time>-->
                    <span class="time">细嗅蔷薇natalie&nbsp;&nbsp;&nbsp;&nbsp;5179&nbsp;做过</span>
                  </div>
                </div>
              </el-card>
              <el-card   :body-style="{ padding: '0px' }">
                <img src="../../static/xxcp/12.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card  :body-style="{ padding: '0px' }">
                <img src="../../static/xxcp/12.jpg" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">111111</time>
                  </div>
                </div>
              </el-card>
              <el-card :body-style="{ padding: '0px' }">
                <img src="../../static/xxcp/12.jpg" class="image">
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
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {};
    },
    methods: {
      xia () {
        this.$router.push({path: '/recClass/homeCooking'});
      },
      handleOpen(key, keyPath) {
        console.log(key, keyPath);
      },
      handleClose(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>

<style scoped>
  .homeCook{
    width: 1000px;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 50px;
  }
  .xiangqing{
    width: 100%;
    margin-top: 30px;
  }
  .xiangqing .biaoqian{
    width: 20%;
  }
  .xiangqing .biaoqian li{
    margin-bottom: 5px;
    padding: 0 !important;
  }
  .zhehe /deep/ .el-submenu__title{
    padding-left: 0 !important;
  }
  .zhehe /deep/ .el-menu-item-group__title{
    padding-left: 0px !important;
  }
  .zhehe /deep/ .el-menu{
    border-right: 0;
  }
  .zhehe /deep/ .el-submenu__icon-arrow{
    right: 0;
  }
  .zhucai h1{
    margin: 0 0 16px;
    line-height: 1.2;
    font-weight: 700;
    word-break: break-all;
    font-size: 34px;
  }
  .zhucai i{
    display: inline-block;
    margin: 0 10px;
  }
  .zhucai span{
    color: #dd3915;
  }
  .zhucai ul,
  .zuixin ul{
    margin-top: 30px;
  }
  .zhucai ul .info{
    margin-left: 15px;
  }
  .zuixin li {
    position: relative;
  }
  .zuixin ul .info{
    position: absolute;
    left: 160px;
  }
  .zhucai ul li,
  .zuixin ul li{
    overflow: hidden;
    margin-bottom: 20px;
  }
  .zhucai ul li h3,
  .zuixin ul li h3{
    font-size: 20px;
    font-weight: 700;
    line-height: 1.4;
    color: #222222;
  }
  .zhucai ul li h3 span,
  .zuixin ul li h3 span{
    display: inline-block;
    background-color: #e7e1cd;
    color: #7f828b;
    font-size: 12px;
    margin-left: 10px;
    padding: 0 3px;
  }
  .zhucai .info p,
  .zuixin .info p{
    width: 200px;
    color: #9c6730;
    font-size: 14px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .zhucai .info h4,
  .zuixin .info h4{
    color: #909090;
    font-size: 13px;
    margin-top: 8px;
  }
  .zhucai .info h4 span,
  .zuixin .info h4 span{
    color: #72a46d;
    font-weight: 700;
    margin-top: 8px;
  }
  .zhucai .info h6,
  .zuixin .info h6{
    font-size: 13px;
    color: #909090;
    margin-top: 8px;
  }
  .zuixin{
    margin-left: 20px;
  }
  .zuixin .info img{
    width: 135px;
    height: 100px;
    margin-right: 15px;
  }
  .zuixin h2{
    font-size: 20px;
    font-weight: 700;
    color: #c0ae7d;
    margin-bottom: 30px;
  }
  .zuixin h2 span{
    display: inline-block;
    font-size: 14px;
    margin-left: 15px;
    color: #dd3915;
  }
  .zhucai /deep/ .el-pagination.is-background .el-pager li{
    background-color: #fff;
  }
  .zhucai /deep/ .el-pagination.is-background .el-pager li:not(.disabled).active{
    background-color: #dd3915;
    color: #fff;
  }
  .xfcdqbcd /deep/ .el-col-8{
    width: 100%;
  }
  .xfcdqbcd /deep/ .el-card{
    width: 85%;
    margin-bottom: 20px;
  }
  .xfcdqbcd /deep/ .el-card:nth-child(2n){
    margin-left: 2%;
    margin-bottom: 5%;
  }
</style>
