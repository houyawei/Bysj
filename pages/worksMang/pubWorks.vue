<template>
  <div class="wk">
    <div class="timu">
      <el-input class="elInput" v-model="input" placeholder="添加菜谱名称"></el-input>
    </div>
    <div class="fengmian">
      <el-upload
        class="avatar-uploader"
        action="https://jsonplaceholder.typicode.com/posts/"
        :headers="hed"
        :show-file-list="false"
        :on-success="handleAvatarSuccess"
        :before-upload="beforeAvatarUpload">
        <img v-if="imageUrl1" :src="imageUrl1" class="avatar">
        <i v-else class="el-icon-plus avatar-uploader-icon"></i>
        <div class="el-upload__text" v-if="fengFlse">添加封面</div>
      </el-upload>
    </div>
    <div class="tjms">
      <el-input
        type="textarea"
        :autosize="{ minRows: 6}"
        placeholder="请输入添加菜谱的描述"
        v-model="textarea">
      </el-input>
    </div>
    <div class="ylbz">
      <div class="yongliao">
        <h3>用料</h3>
        <el-table :data="tableData" style="width: 100%" border>
          <el-table-column label="食材" min-width="180" align="center">
            <template slot-scope="scope">
              <el-input v-model="scope.row.shicai" placeholder="请输入内容"></el-input>
            </template>
          </el-table-column>
          <el-table-column label="用量" min-width="180" align="center">
            <template slot-scope="scope">
              <el-input v-model="scope.row.yonglinag" placeholder="请输入内容"></el-input>
            </template>
          </el-table-column>
          <el-table-column fixed="right" label="操作" width="120" align="center">
            <template slot-scope="scope">
              <el-button @click.native.prevent="deleteRow(scope.$index, tableData)" type="text" size="small">
                移除
              </el-button>
            </template>
          </el-table-column>
        </el-table>
        <el-button type="primary" @click="zhuijia" class="zjyh">追加一行</el-button>
      </div>
      <div class="zuofa">
        <h3>做法</h3>
        <ul>
          <li v-for="(item, index) in data" :key="index">
            <div class="index fl">{{ index + 1}}</div>
            <div class="bzText fl">
              <el-input
                type="textarea"
                :autosize="{ minRows: 6}"
                placeholder="添加步骤"
                v-model="item.textarea">
              </el-input>
            </div>
            <div class="bzTu fl">
              <el-upload
                class="avatar-uploader"
                action="https://jsonplaceholder.typicode.com/posts/"
                :headers="hed"
                :show-file-list="false"
                :on-success="handleAvatarSuccess2"
                :before-upload="beforeAvatarUpload2">
                <img v-if="imageUrl2" :src="imageUrl2" class="avatar">
                <i v-else class="el-icon-plus avatar-uploader-icon"></i>
                <div class="el-upload__text" v-if="fengFlse">添加步骤图</div>
              </el-upload>
            </div>
          </li>
        </ul>
        <el-button type="primary" @click="bzzj" class="zjyh">追加步骤</el-button>
      </div>
      <div class="xts">
        <h4>小贴士</h4>
        <el-input
          type="textarea"
          :autosize="{ minRows: 6}"
          placeholder="添加小贴士"
          v-model="textarea">
        </el-input>
      </div>
      <el-button type="primary" class="zhfabu">发布菜谱</el-button>
    </div>
    <div class="meiju fl">
      <h3>创建菜谱的人是厨房里的天使</h3>
      <p>下厨房鼓励大家上传自己原创的菜谱信息； 转载、翻译的内容请在简介里表明出处。</p>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        imageUrl1: '',
        imageUrl2: '',
        hed: {
            Accept: 'application/json, text/plain, /'
        },
        input: '',
        textarea: '',
        tableData: [{
          shicai: '2016-05-02',
          yonglinag: '王小虎',
        }, {
          hicai: '2016-05-02',
          yonglinag: '王小虎',
        }, {
          hicai: '2016-05-02',
          yonglinag: '王小虎',
        }, {
          hicai: '2016-05-02',
          yonglinag: '王小虎',
        }],
        data: [
          {textarea: ''}
        ],
        fengFlse: true
      };
    },
    methods: {
      bzzj () {
        let obj = {textarea: ''};
        this.data.push(obj)
      },
      zhuijia () {
        let obj = {
          hicai: '',
          yonglinag: '',
        };
        this.tableData.push(obj)
      },
      deleteRow(index, rows) {
        rows.splice(index, 1);
      },
      handleAvatarSuccess(res, file) {
        this.imageUrl1 = URL.createObjectURL(file.raw);
        this.fengFlse = false;
      },
      beforeAvatarUpload(file) {
        const isJPG = file.type === 'image/jpeg';
        const isLt2M = file.size / 1024 / 1024 < 2;

        if (!isJPG) {
          this.$message.error('上传头像图片只能是 JPG 格式!');
        }
        if (!isLt2M) {
          this.$message.error('上传头像图片大小不能超过 2MB!');
        }
        return isJPG && isLt2M;
      },
      handleAvatarSuccess2(res, file) {
        this.imageUrl2 = URL.createObjectURL(file.raw);
        this.fengFlse = false;
      },
      beforeAvatarUpload2(file) {
        const isJPG = file.type === 'image/jpeg';
        const isLt2M = file.size / 1024 / 1024 < 2;

        if (!isJPG) {
          this.$message.error('上传头像图片只能是 JPG 格式!');
        }
        if (!isLt2M) {
          this.$message.error('上传头像图片大小不能超过 2MB!');
        }
        return isJPG && isLt2M;
      }
    }
  }
</script>

<style scoped>
  .wk{
    width: 1015px;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 50px;
    position: relative;
  }
  .timu{
    width: 60%;
  }
  .timu /deep/ .el-input__inner{
    height: 50px;
    background-color: #fffce9;
    color: #888;
    border: 0;
  }
  .fengmian{
    width: 60%;
    min-height: 300px;
    margin-top: 20px;
    background-color: #f0f2f5;
  }
  .fengmian .avatar-uploader .el-upload {
    border: 1px dashed #d9d9d9;
    border-radius: 6px;
    cursor: pointer;
    position: relative;
    overflow: hidden;
  }
  .fengmian .avatar-uploader .el-upload:hover {
    border-color: #409EFF;
  }
  .fengmian .avatar-uploader-icon {
    font-size: 28px;
    color: #8c939d;
    width: 588px;
    height: 78px;
    line-height: 278px;
    text-align: center;
  }
  .fengmian .avatar {
    width: 100%;
    /*height: 178px;*/
    display: block;
  }
  .tjms{
    width: 60%;
    min-height: 150px;
    margin-top: 20px;
  }
  .ylbz{
    width: 60%;
    margin-top: 20px;
    overflow: hidden;
    text-align: center;
  }
  .ylbz /deep/ .el-input__inner{
    border: 0;
  }
  .yongliao h3,
  .zuofa h3{
    color: #c0ae7d;
    margin-bottom: 10px;
    font-size: 24px;
    font-weight: 700;
  }
  .yongliao .zjyh{
    margin-top: 15px;
  }
  .zuofa{
    margin-top: 20px;
  }
  .zuofa ul li {
    overflow: hidden;
    margin-bottom: 15px;
  }
  .zuofa ul li .bzText{
    width: 45%;
  }
  .zuofa ul li .bzTu{
    width: 48%;
    margin-left: 2%;
  }
  .zuofa ul li .index{
    display: inline-block;
    margin-right: 15px;
    color: #c0ae7d;
    font-size: 24px;
    font-weight: 700;
  }
  .bzTu .avatar-uploader{
    /*background-color: #e7e1cd;*/
    padding-bottom: 10px;
  }
  .bzTu .avatar-uploader .el-upload {
    border: 1px dashed #d9d9d9;
    border-radius: 6px;
    cursor: pointer;
    position: relative;
    overflow: hidden;
  }
  .bzTu .avatar-uploader .el-upload:hover {
    border-color: #409EFF;
  }
  .bzTu .avatar-uploader-icon {
    font-size: 28px;
    color: #8c939d;
    width: 178px;
    height: 78px;
    line-height: 178px;
    text-align: center;
  }
  .bzTu .avatar {
    width: 178px;
    height: 178px;
    display: block;
  }
  .xts{
    width: 100%;
    min-height: 150px;
    margin-top: 30px;
    background-color: #f5f6f5;
    padding: 32px;
    font-size: 16px;
    color: #222;
  }
  .xts /deep/ .el-textarea__inner{
    background-color: #f5f6f5;
    width: 90%;
  }
  .zhfabu{
    margin-top: 20px;
    width: 120px;
    height: 50px;
    font-size: 22px;
  }
  .meiju{
    width: 35%;
    min-height: 150px;
    margin-left: 5%;
    background-color: #f5f6f5;
    padding: 16px 20px 40px;
    text-align: center;
    position: absolute;
    top: 20px;
    right: 0px;
  }
  .meiju h3{
    font-size: 20px;
    font-weight: 700;
    color: #c0ae7d;
  }
  .meiju p{
    font-size: 14px;
    color: #909090;
  }
</style>
