<template>
  <div class="footer">
    <div class="personalLink">
      <a href="https://www.yuque.com/u1353204">语雀</a><span>|</span>
      <a href="https://github.com/toaloe">GitHub</a><span>|</span>
      <a href="https://www.zhihu.com/people/aloe-66">知乎</a><span>|</span>
      <a href="https://weibo.com/5188102719/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1">微博</a>
    </div>
  </div>
</template>

<script>
export default {
  name:'navFooter'
}
</script>

<style lang="scss" scoped>
.footer{
  border-top: 3px solid rgb(246, 123, 69);
  background-color: rgb(29, 29, 31);
  .personalLink{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(218, 214, 213);
    a{
      color: rgb(218, 214, 213);
    }
  }
}
</style>