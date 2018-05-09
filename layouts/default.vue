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
    beforeMount () {
      this.minHeight = document.body.clientHeight - 188
    },
    mounted () {
      // this.minHeight = document.body.clientHeight - 188
    }
  }
</script>
<style>
  .nuxt{
    width: 1015px;
    margin: 0 auto;
    overflow: hidden;
  }
</style>
