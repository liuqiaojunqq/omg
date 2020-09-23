<template>
  <div id="app">
    <!-- 挂载到DOM -->
    卡圣诞节复活节开始
    <FooterNav />
  </div>
</template>
<script>
// 组件引用
import FooterNav from '@/components/FooterNav/FooterNav.vue'
// 注册组件到components
export default {
  components: {
    FooterNav
  }
}
</script>
<style scoped lang='stylus'>
@import url(./assets/stylus/reset.styl);
</style>
