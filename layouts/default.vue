<template>
  <div class="m-container">
    <toolbar />
    <nuxt />
    <foot />
  </div>
</template>

<style lang="sass">
  *
    font-family: "Helvetica", "Arial", "文泉驛正黑", "WenQuanYi Zen Hei", "黑體-繁", "Heiti TC", "微軟正黑體", "Microsoft JhengHei"
    line-height: 1.5
  body
    background-color: #171B1C
  h1
    font-size: 4rem
  h2
    font-size: calc(24px + 1vw)
    font-weight: 500
  h3
    font-szie: 2rem
  h4 p
    font-szie: 1rem
  h1, h2, h3, h4, p
    color: white
    margin: 0
  ul
    padding: 0
</style>

<script>
import Toolbar from '@/components/Toolbar.vue'
import Foot from '@/components/Footer.vue'

export default {
  components: {
    Toolbar,
    Foot
  }
}
</script>
