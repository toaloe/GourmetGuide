<template>
  <div class="footer">
    
    <div class="logo">
      <i class="iconfont icon-icon"></i><span>中华美食集</span>
    </div>
    
    <div class="personalLink">
      <a href="https://www.yuque.com/u1353204">语雀</a><span>|</span>
      <a href="https://github.com/toaloe">GitHub</a><span>|</span>
      <a href="https://www.zhihu.com/people/aloe-66">知乎</a><span>|</span>
      <a href="https://weibo.com/5188102719/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1">微博</a>
    </div>
    <div class="TechStack">
      <span>技术栈</span><span>|</span>
      <span>HTML</span><span>|</span>
      <span>CSS</span><span>|</span>
      <span>JavaScript</span><span>|</span>
      <span>ES6</span><span>|</span>
      <span>Vue</span><span>|</span>
      <span>Vue-router</span><span>|</span>
      <span>axios</span>
    </div>
    <div class="study">
      <span>学习</span><span>|</span>
      <a href="https://www.w3school.com.cn/index.html">HTML到CSS</a><span>|</span>
      <a href="https://es6.ruanyifeng.com/">ES6</a><span>|</span>
      <a href="https://cn.vuejs.org/">Vue</a><span>|</span>
      <a href="https://webpack.js.org/">webpack</a><span>|</span>
      <a href="https://vuex.vuejs.org/zh/">Vuex</a><span>|</span>
      <a href="https://router.vuejs.org/zh/">Vue-router</a><span>|</span>
      <a href="https://element.eleme.io/#/en-US">Element-UI</a><span>|</span>
      <a href="https://router.vuejs.org/zh/">Vue-router</a>
    </div>
  </div>
</template>

<script>
export default {
  name:'navFooter'
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/basic.scss';
.footer{
  border-top: 3px solid rgb(246, 123, 69);
  background-color: $colorH;
  height: 200px;
  .logo{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 10px;
    .icon-icon{
      font-size: 40px;
    }
    span{
      color: $colorA;
      font-size: 20px;
      margin-left: 15px;
    }
  }
  .personalLink{
    display: flex;
    justify-content: center;
    align-items: center;
    color: $colorA;
    margin-bottom: 10px;
    font-size: 16px;
    a{
      color: $colorA;
    }
    span{
      margin: 0 10px;
    }
  }
  .TechStack{
    text-align: center;
    span{
      color: $colorA;
      font-size: 16px;
      margin-left: 10px;
    }
    margin-bottom: 10px;
  }
  .study{
    display: flex;
    justify-content: center;
    align-items: center;
    color: $colorA;
    margin-bottom: 10px;
    font-size: 16px;
    a{
      color: $colorA;
    }
    span{
      margin: 0 10px;
    }
  }
}
</style>