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
          <div class="jionUs" @mouseenter="showErwei" @mouseleave="hideErwei">交流学习</div>
          <div class="login"><a href="javaScript:;">登录</a></div>
        </div>
      </div>
    </div>
    <div v-if="this.isShowErwei" class="erwei">
          <img src="@/assets/images/wechat.jpg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name:'navHeader',
  data(){
    return {
      isShowErwei:false
    }
  },
  methods:{
    showErwei(){
      this.isShowErwei=true;
    },
    hideErwei(){
      this.isShowErwei=false;
    }
  }
}
</script>

style <style lang="scss" scoped>
.header{
  .navTop{
    height: 50px;
    line-height: 50px;
    background-color: rgb(29, 29, 31);
    font-size: 15px;
    .container{
      display: flex;
      justify-content: center;
      align-items: center;
      .navLeft{
        margin-right: 900px;
        a{
          color: rgb(218, 214, 213);
          margin-left: 20px;
        }
      }
      .navRigth{
        .login{
          display: inline-block;
          a{
            color: rgb(218, 214, 213);
          }
        }
        .jionUs{
          display: inline-block;
          margin-right: 20px;
          color: rgb(218, 214, 213);
          cursor: pointer;
        }
      }
    }
  }
  .erwei{
    position: fixed;
    left: 1410px;
    top: 50px;
    border: 1px solid #ccc;
    img{
      width: 200px;
      height: 200px;
      margin: 3px;
    }
  }
  // .none{
  //   display: none;
  // }
}

</style>