<template>
  <!--全站更新-->
  <div class="wk">
    <div class="tit">
      <h3 class="fl" :class="{h3Act: h3act}" @click="clickPath(0)">我关注的更新</h3>
      <h3 class="fl" :class="{h3Act: !h3act}" @click="clickPath(1)">全站的更新</h3>
    </div>
    <div class="leibie">
      <ul>
        <li class="fl">最新上传</li>
        <li class="fl">正在流行</li>
        <li class="fl">24小时最佳</li>
      </ul>
    </div>
    <div class="tu">
      <el-row>
        <el-col :span="8">
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
          <el-card class="fl" :body-style="{ padding: '0px' }">
            <img src="../../static/xxcp/16.jpg" class="image">
            <div style="padding: 14px;" class="userInfo">
              <span class="caiming">好吃的汉堡</span>
              <span class="miaoshu">额外又加了耗油和五香粉</span>
              <div class="bottom clearfix">
                <span class="shijian">7分钟前 <i>1 <i class="iconfont icon-zan"></i></i></span>
                <div class="img">
                  <img src="../../static/xxcp/17.jpg" alt="">
                </div>
                <span class="name"> 手机用户0681_in1q</span>
              </div>
            </div>
          </el-card>
        </el-col>
      </el-row>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        h3act: false
      }
    },
    methods: {
      clickPath (id) {
        if (id === 1) {
          this.h3act = false;
          this.$router.push({path: '/worksNews/totalStaUpdate'});
        }
        if (id === 0) {
          this.h3act = true;
          this.$router.push({path: '/worksNews'});
        }
      }
    }
  }
</script>

<style scoped>
  .wk{
    width: 1000px;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 50px;
  }
  .tit{
    width: 100%;
    background-color: #f5f6f5;
    position: relative;
    height: 50px;
  }
  .tit h3{
    display: inline-block;
    text-align: center;
    width: 150px;
    height: 50px;
    line-height: 50px;
    cursor: pointer;
  }
  .tit h3:nth-child(2){
    border-left: 1px solid #fff;
    border-right: 1px solid #fff;
  }
  .tit h3:hover,
  .tit .h3Act{
    background-color: #dd3915;
    color: #fff;
  }
  .leibie {
    width: 100%;
    margin: 20px 0;
    overflow: hidden;
  }
  .leibie ul{
    float: right;
  }
  .leibie ul li:nth-child(2){
    margin: 0 20px;
    color: #222;
  }
  .leibie ul li{
    padding: 0 10px;
    box-sizing: border-box;
  }
  .leibie ul li:hover{
    color: #fff;
    background-color: #dd3915;
    cursor: pointer;
  }
  .tu /deep/ .el-col-8{
    float: left;
    width: 100%;
  }
  .tu /deep/ .el-card{
    margin-left: 30px;
    margin-bottom: 30px;
  }
  .userInfo span{
    display: inline-block;
    margin: 10px 0;
  }
  .userInfo .caiming {
    overflow: hidden;
    color: #dd3915;
    text-decoration: none;
    font-size: 16px;
  }
  .userInfo .miaoshu{
    display: block;
    color: #333;
    overflow: hidden;
    font-size: 12px;
  }
  .userInfo .shijian{
    display: block;
    font-size: 12px;
    color: #7f828b;
    margin-top: 30px;
  }
  .userInfo .shijian i{
    float: right;
    margin-right: 10px;
    margin-left: 10px;
  }
  .userInfo .img{
    float: left;
    overflow: hidden;
    margin-right: 20px;
   }
  .userInfo .img img{
    width: 30px;
    height: 30px;
    border-radius: 50%;
  }
  .userInfo .name{
    margin-top: -6px;
    color: #dd3915;
    font-size: 12px;
  }
</style>
