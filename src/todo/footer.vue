<template>
  <header class="footer">
    <p>Written by {{author}}</p>
  </header>
</template>

<script>
export default {
  data() {
    return {
      author: 'Jenny'
    }
  }
}
</script>

<style lang="stylus" scoped>
  .footer
    text-align center
    p
      font-size 14px
      color #4b4b4b
      font-weight 300
      margin 20px
</style>