<template>
  <div class="top">
    <div class="cen">
      <nuxt-link to="/">
        <div class="logo fl"></div>
      </nuxt-link>
      <div class="login fr">
        <div class="touxiang fl" @click="pathInfo('/worksMang')"></div>
        <span class="fl">|</span>
        <div class="zhuce fl" @click="pathInfo('/worksMang/registered')"></div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        input5: '',
        caipu: false
      }
    },
    methods: {
      dataDetails (id) {
        if (id === 1) {
          this.caipu = true;
        }
      },
      hiddenDetail (id) {
        if (id === 1) {
          this.caipu = false;
        }
      },
      pathInfo (path) {
        this.$router.push({path: path});
      }
    }
  }
</script>

<style scoped>
  .top{
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 10;
    box-shadow: 0 2px 2px -2px rgba(0,0,0,.08);
    height: 70px;
    background-color: #fff;
  }
  .cen{
    width: 1015px;
    margin: 0 auto;
    position: relative;
  }
  .top .logo{
    display: inline-block;
    width: 120px;
    height: 40px;
    margin-top: 15px;
    text-indent: -99em;
    background: url('../static/zww-logo.png') no-repeat;
    background-size: 120px 40px;
  }
  .top .serach{
    width: 400px;
    margin-top: 15px;
    margin-left: 30px;
  }
  .top .serach /deep/ .el-input-group__append button.el-button {
    background-color: #dd3915;
  }
  .top .serach /deep/ .el-icon-search{
    color: #fff;
  }
  .top .menu{
    margin-top: 25px;
    margin-left: 20px;
  }
  .top .menu ul li{
    margin-right: 15px;
  }
  .menu ul li a{
    color: #dd3915;
  }
  .top .login{
    height: 36px;
    width: 112px;
    margin-top: 20px;
  }
  .login .touxiang{
    width: 40px;
    height: 40px;
    background: url("../static/touxiang.png") no-repeat;
  }
  .login .zhuce{
    width: 40px;
    height: 40px;
    margin-left: 10px;
    background: url("../static/touxiang.png") no-repeat;
  }
  .login span{
    display: inline-block;
    font-size: 20px;
  }
  .caipu{
    width: 440px;
    position: absolute;
    top: 65px;
    right: 100px;
    background-color: #f5f6f5;
    box-shadow: 0 0 1px #e8eae8;
    padding: 16px 16px 0;
    box-sizing: border-box;
  }
  .caipu .fl{
    width: 28%;
    margin-left: 20px;
    overflow: hidden;
  }
  .caipu h3{
    color: #909090;
    margin-bottom: 4px;
    font-size: 16px;
    line-height: 36px;
  }
  .caipu li{
    width: 65px;
    text-align: center;
    color: #dd3915;
    font-size: 14px;
    margin-bottom: 10px;
    cursor: pointer;
  }
  .caipu li:hover{
    background-color: #dd3915;
    color: #ffffff;
  }
  .caipu .qbfl{
    width: 400px;
    float: left;
    text-align: center;
    height: 50px;
    line-height: 50px;
    color: #dd3915;
    border-top: 2px solid #fff;
  }
</style>
