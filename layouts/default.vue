<template>
  <div>
    <Nav></Nav>
    <nuxt v-bind:style="{ minHeight: minHeight + 'px' }"/>
    <Foot></Foot>
    <div>3333</div>
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
