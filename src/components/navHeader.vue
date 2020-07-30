<template>
  <div class="header">
    <div class="navTop">
      <div class="container">
        <div class="navLeft">
        <a href="javaScript:;">舌尖中国</a>
        <a href="javaScript:;">八大菜系</a>
        <a href="javaScript:;">料理小试</a>
      </div>
      <div class="navRigth">
        <div class="jionUs">交流学习</div>
        <div class="login"><a href="javaScript:;">登录</a></div>
        
      </div>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name:'navHeader'
}
</script>

style <style lang="scss" scoped>
.header{
  .navTop{
    height: 50px;
    line-height: 50px;
    background-color: rgb(175, 170, 170);
    font-size: 15px;
    .container{
      display: flex;
      justify-content: center;
      align-items: center;
      .navLeft{
        margin-right: 900px;
        a{
          color: rgb(37, 36, 36);
          margin-left: 20px;
        }
      }
      .navRigth{
        .login{
          display: inline-block;
          a{
            color: rgb(37, 36, 36);
          }
        }
        .jionUs{
          // float: right;
          display: inline-block;
          margin-right: 20px;
        }
      }
    }
    
  }
}

</style>