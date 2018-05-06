<template>
  <div class="wk">
    <h1 class="Newzh">经常登录的同志是好同志</h1>
    <div class="zhuceInfo">
      <el-form :model="ruleForm" :rules="rules" ref="ruleForm" label-width="100px" class="demo-ruleForm">
        <el-form-item label="手机号：" prop="phone">
          <el-input placeholder="请输入内容" v-model="ruleForm.phone" class="input-with-select">
            <el-select v-model="select" slot="prepend" placeholder="请选择">
              <el-option label="+87" value="1"></el-option>
              <el-option label="+88" value="2"></el-option>
              <el-option label="+89" value="3"></el-option>
            </el-select>
          </el-input>
        </el-form-item>
        <el-form-item label="密码：" prop="pwd">
          <el-input v-model="ruleForm.pwd" placeholder="设置密码（不少于6位）"></el-input>
        </el-form-item>
        <el-form-item>
          <el-button type="primary" @click="submitForm('ruleForm')" class="pri">登录</el-button>
        </el-form-item>
      </el-form>
    </div>
  </div>
</template>

<script>
  export default {
    layout: 'login',
    data() {
      return {
        input5: '',
        input4: '',
        select: '+86',
        ruleForm: {
          phone: '',
          pwd: '',
          val: '',
          name: '',
          pwd2: ''
        },
        rules: {
          name: [
            {required: true, message: '请输入昵称', trigger: 'change'}
          ],
          phone: [
            {required: true, message: '请输入手机号', trigger: 'change'}
          ],
          val: [
            {type: 'date', required: true, message: '请输入验证码', trigger: 'change'}
          ],
          pwd: [
            {type: 'date', required: true, message: '请输入密码', trigger: 'change'}
          ],
          pwd2: [
            {type: 'date', required: true, message: '请确认密码', trigger: 'change'}
          ],
          type: [
            {type: 'array', required: true, message: '请至少选择一个活动性质', trigger: 'change'}
          ],
          resource: [
            {required: true, message: '请选择活动资源', trigger: 'change'}
          ],
          desc: [
            {required: true, message: '请填写活动形式', trigger: 'blur'}
          ]
        }
      };
    }
  }
</script>

<style scoped>
  .wk{
    width: 1015px;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 50px;
    overflow: hidden;
  }
  .Newzh{
    width: 380px;
    font-size: 34px;
    font-weight: 700;
    margin: 30px auto;
  }
  .zhuceInfo{
    width: 500px;
    margin: 0 auto;
    overflow: hidden;
  }
  .zhuceInfo /deep/ .el-input-group__prepend .el-input{
    width: 100px !important;
  }
  .zhuceInfo .pri{
    margin-left: 150px;
  }
  .zhuceInfo .xieyi{
    color: #dd3915;
  }
</style>
