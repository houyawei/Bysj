<template>
  <div class="top">
    <div class="cen">
      <div class="logo fl">
      </div>
      <div class="serach fl">
        <el-input placeholder="搜索菜谱、食谱" v-model="input5" class="input-with-select">
          <el-button slot="append" icon="el-icon-search"></el-button>
        </el-input>
      </div>
      <div class="menu fl">
        <ul>
          <li v-for="(item, index) in relations" :key="index" class="fl">
            <nuxt-link :to="item.path">{{ item.text }}</nuxt-link>
          </li>
        </ul>
      </div>
      <div class="login fl">
        <div class="touxiang fl"></div>
        <span class="fl">|</span>
        <div class="zhuce fl"></div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        input5: '',
        relations: [
          {text: '首页', path: '/membOnly', icon: 'lc-shouye1'},
          {text: '菜谱分类', path: '/membOnly', icon: 'lc-shouye1'},
          {text: '菜单', path: '/membOnly', icon: 'lc-shouye1'},
          {text: '作品动态', path: '/membOnly', icon: 'lc-shouye1'},
        ],
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
    width: 1000px;
    margin: 0 auto;
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
</style>
