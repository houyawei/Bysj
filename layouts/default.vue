<template>
  <div>
    <Nav></Nav>
    <nuxt v-bind:style="{ minHeight: minHeight + 'px' }" class="nuxt"/>
    <Foot></Foot>
  </div>
</template>

<script>
  import Nav from '~/components/Nav.vue'
  import Foot from '~/components/Foot.vue'
  import '../assets/font/iconfont.css'

  export default {
    components: {
      Nav,
      Foot
    },
    data () {
      return {
        minHeight: 0
      }
    },
    mounted () {
      this.minHeight = document.body.clientHeight - 80
    }
  }
</script>
<style>
  .nuxt{
    width: 1000px;
    margin: 0 auto;
  }
</style>
