<template>
  <div>
    <Nav2></Nav2>
    <nuxt v-bind:style="{ minHeight: minHeight + 'px' }" class="nuxt"/>
  </div>
</template>

<script>
  import Nav2 from '~/components/Nav2.vue'
  import '../assets/font/iconfont.css'

  export default {
    components: {
      Nav2,
    },
    data () {
      return {
        minHeight: 0
      }
    },
    mounted () {
      this.minHeight = document.body.clientHeight - 188
    }
  }
</script>

<style scoped>
  .nuxt{
    width: 1000px;
    margin: 0 auto;
    overflow: hidden;
  }
</style>
