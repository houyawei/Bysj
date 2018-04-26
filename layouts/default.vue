<template>
  <div>
    <Nav></Nav>
    <nuxt v-bind:style="{ minHeight: minHeight + 'px' }"/>
    ssssｓｓｓ
    <Foot></Foot>
  </div>
</template>

<script>
  import Nav from '~/components/Nav.vue'
  import Foot from '~/components/Foot.vue'

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
      this.minHeight = document.body.clientHeight - 133
    }
  }
</script>

<style></style>
