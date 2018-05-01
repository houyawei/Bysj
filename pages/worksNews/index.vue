<template>
  <!--作品动态-->
  <div class="wk">
    <div class="tit">
      <h3 class="fl">我关注的更新</h3>
      <h3 class="fl">全站的更新</h3>
    </div>
    <ul class="zp-list">
      <li class="lii">
        <div class="list-tit">
          <img src="../../static/xxcp/13.jpg" alt="">
          <h3><span>鹏妈在奔跑</span> 做过 <span>鸡蛋羹包馄饨</span><i>13分钟前</i></h3>
        </div>
        <div class="neirong">
          <img src="../../static/xxcp/14.jpg" alt="">
          <p>儿子至今都深爱，等我老了还会做给他吃，小时候他是靠这个维持生命....... #晚餐•2018年5月1日#</p>
          <h4>鸡蛋羹包馄饨的做法</h4>
          <div class="zan">
            <i class="iconfont icon-zan" :class="{iAct:act}" @click="actClick"></i>
            <span>49</span>赞
          </div>
        </div>
        <div class="pinglun">
          <div>
            <input type="text">
            <input type="button" value="评论">
          </div>
          <ul>
            <li>
              <img src="../../static/xxcp/15.jpg" alt="">
              <p><span>满池烟水</span><i>做的真好👍👍</i></p>
            </li>
          </ul>
        </div>
      </li>
      <li class="lii">
      <div class="list-tit">
        <img src="../../static/xxcp/13.jpg" alt="">
        <h3><span>鹏妈在奔跑</span> 做过 <span>鸡蛋羹包馄饨</span><i>13分钟前</i></h3>
      </div>
      <div class="neirong">
        <img src="../../static/xxcp/14.jpg" alt="">
        <p>儿子至今都深爱，等我老了还会做给他吃，小时候他是靠这个维持生命....... #晚餐•2018年5月1日#</p>
        <h4>鸡蛋羹包馄饨的做法</h4>
        <div class="zan">
          <i class="iconfont icon-zan" :class="{iAct:act}" @click="actClick"></i>
          <span>49</span>赞
        </div>
      </div>
      <div class="pinglun">
        <div>
          <input type="text">
          <input type="button" value="评论">
        </div>
        <ul>
          <li>
            <img src="../../static/xxcp/15.jpg" alt="">
            <p><span>满池烟水</span><i>做的真好👍👍</i></p>
          </li>
        </ul>
      </div>
    </li>
      <li class="lii">
        <div class="list-tit">
          <img src="../../static/xxcp/13.jpg" alt="">
          <h3><span>鹏妈在奔跑</span> 做过 <span>鸡蛋羹包馄饨</span><i>13分钟前</i></h3>
        </div>
        <div class="neirong">
          <img src="../../static/xxcp/14.jpg" alt="">
          <p>儿子至今都深爱，等我老了还会做给他吃，小时候他是靠这个维持生命....... #晚餐•2018年5月1日#</p>
          <h4>鸡蛋羹包馄饨的做法</h4>
          <div class="zan">
            <i class="iconfont icon-zan" :class="{iAct:act}" @click="actClick"></i>
            <span>49</span>赞
          </div>
        </div>
        <div class="pinglun">
          <div>
            <input type="text">
            <input type="button" value="评论">
          </div>
          <ul>
            <li>
              <img src="../../static/xxcp/15.jpg" alt="">
              <p><span>满池烟水</span><i>做的真好👍👍</i></p>
            </li>
          </ul>
        </div>
      </li>
      <li class="lii">
        <div class="list-tit">
          <img src="../../static/xxcp/13.jpg" alt="">
          <h3><span>鹏妈在奔跑</span> 做过 <span>鸡蛋羹包馄饨</span><i>13分钟前</i></h3>
        </div>
        <div class="neirong">
          <img src="../../static/xxcp/14.jpg" alt="">
          <p>儿子至今都深爱，等我老了还会做给他吃，小时候他是靠这个维持生命....... #晚餐•2018年5月1日#</p>
          <h4>鸡蛋羹包馄饨的做法</h4>
          <div class="zan">
            <i class="iconfont icon-zan" :class="{iAct:act}" @click="actClick"></i>
            <span>49</span>赞
          </div>
        </div>
        <div class="pinglun">
          <div>
            <input type="text">
            <input type="button" value="评论">
          </div>
          <ul>
            <li>
              <img src="../../static/xxcp/15.jpg" alt="">
              <p><span>满池烟水</span><i>做的真好👍👍</i></p>
            </li>
          </ul>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        act: false
      }
    },
    methods: {
      actClick () {
        this.act = true
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
    width: 60%;
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
  }
  .tit h3:nth-child(2){
    border-left: 1px solid #fff;
    border-right: 1px solid #fff;
  }
  .tit h3:hover{
    background-color: #dd3915;
    color: #fff;
  }
  .zp-list{
    width: 60%;
    padding: 15px;
    margin-top: 20px;
    box-sizing: border-box;
    position: relative;
  }
  .zp-list .lii{
    margin-bottom: 20px;
    border: 1px solid #e7e1cd;
  }
  .zp-list .list-tit{
    overflow: hidden;
  }
  .zp-list .list-tit img{
    float: left;
    width: 50px;
    height: 50px;
    border-radius: 50%;
  }
  .zp-list .list-tit h3{
    width: 85%;
    font-size: 16px;
    font-weight: 700;
    position: absolute;
    left: 80px;
    top: 30px;
  }
  .zp-list .list-tit h3 span{
    overflow: hidden;
    color: #dd3915;
    font-weight: 400;
    font-size: 14px;
  }
  .zp-list .list-tit h3 i{
    float: right;
    color: #7f828b;
    font-weight: 400;
    font-size: 12px;
  }
  .zp-list .neirong{
    margin-top: 20px;
    width: 100%;
  }
  .neirong{
    overflow: hidden;
    position: relative;
  }
  .neirong img{
    width: 200px;
    height: 200px;
    float: left;
  }
  .neirong p,
  .neirong h4{
    margin-left: 220px;
  }
  .neirong p{
    font-family: sans-serif;
    font-size: 16px;
    line-height: 1.6;
    color: #222;
  }
  .neirong h4{
    font-weight: 700;
    font-size: 16px;
    margin-top: 20px;
    color: #dd3915;
  }
  .neirong .zan{
    position: absolute;
    bottom: 10px;
    right: 10px;
    color: #909090;
    font-size: 12px;
  }
  .neirong .zan span{
    display: inline-block;
    margin: 0 6px;
  }
  .neirong .zan i{
    cursor: pointer;
  }
  .neirong .zan .iAct{
    color: #dd3915;
  }
  .zp-list .pinglun{
    width: 100%;
    margin-top: 15px;
    padding-bottom: 15px;
    background-color: #e7e1cd;
    overflow: hidden;
  }
  .pinglun input{
    border: 0;
    margin: 15px;
  }
  .pinglun input:first-child{
    width: 390px;
    height: 30px;
    padding: 6px;
  }
  .pinglun input:last-child{
    width: 100px;
    height: 30px;
    background-color: #dd3915;
    color: #fff;
  }
  .pinglun li img{
    width: 20px;
    height: 20px;
    border-radius: 50%;
    float: left;
    margin: 15px;
    margin-top: 0;
  }
  .pinglun li p{
    font-size: 12px;
    margin-left: 50px;
    vertical-align: baseline;
    color: #7f828b;
  }
  .pinglun li p span{
    margin-right: 15px;
    color: #dd3915;
  }
</style>
