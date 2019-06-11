<template>
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">养猪场音乐</h1>
    <router-link to="/user" class="mine" tag="div">
      <i class="icon-mine"></i>
    </router-link>
  </div>
</template>

<script>
export default {}
</script>

<style lang="stylus">
@import '~common/stylus/variable'
@import '~common/stylus/mixin'
.m-header
  position: relative
  height: 44px
  text-align: center
  color: $color-sub-text
  background: $color-theme
  font-size: 0
  .icon
    display: inline-block
    vertical-align: top
    margin-top: 6px
    width: 32px
    height: 32px
    margin-right: 9px
    bg-image('cloud')
    background-blend-mode: lighten
    background-size: 32px 32px
  .text
    display: inline-block
    vertical-align: top
    line-height: 44px
    font-size: $font-size-large
  .mine
    position: absolute
    top: 0
    right: 0
    .icon-mine
      display: block
      padding: 12px
      font-size: 20px
      color: $color-sub-text
</style>