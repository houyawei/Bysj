<template>
  <div class="top">
    <div class="logo">
      <nuxt-link v-for="(item, index) in relations" :key="index" :to="item.path">{{ item.text }}</nuxt-link>
    </div>
    <div class="serach"></div>
    <div class="menu"></div>
    <div class="login"></div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        relations: [
          {text: '会员专区', path: '/membOnly', icon: 'lc-shouye1'},
        ],
      }
    }
  }
</script>

<style scoped>
  .top{
    width: 100%;
    height: 70px;
    background-color: pink;
  }
</style>
