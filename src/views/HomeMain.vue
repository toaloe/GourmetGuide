<template>
  <div class="homeMain">
    <div class="homeTop">
      <div class="searchContainer">
        <input type="text" placeholder="请输入关键字">
        <a href="javaScript:;"><i class="icon-search iconfont"></i></a>
      </div>
    </div>
    <div class="container">
      <swiper :options="swiperOption"
      >
        <swiper-slide>
          <img src="../assets/images/swiper/food-1.jpg" alt="">
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/images/swiper/food-2.jpg" alt="">
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/images/swiper/food-3.jpg" alt="">
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/images/swiper/food-4.jpg" alt="">
        </swiper-slide>
        <swiper-slide>
          <img src="../assets/images/swiper/food-5.jpg" alt="">
        </swiper-slide>
        <div class="swiper-pagination"  slot="pagination"></div>
        <div class="swiper-button-prev" slot="button-prev"></div>
        <div class="swiper-button-next" slot="button-next"></div>
      </swiper>
      
    </div>
    <div class="showBar">
      <i class="iconfont icon-cai"></i>
      <i class="iconfont icon-segao"></i>
      <i class="iconfont icon-chuancai"></i>
      <i class="iconfont icon-shiwumiantiao"></i>
      <i class="iconfont icon-jiaozi"></i>
      <i class="iconfont icon-shiwu-canpan"></i>
      <i class="iconfont icon-baozi"></i>
      <i class="iconfont icon-shiwu-"></i>
      <i class="iconfont icon-shiwu-1"></i>
      <i class="iconfont icon-shiwu-2"></i>
      <i class="iconfont icon-shiwu-3"></i>
      <i class="iconfont icon-shiwu-4"></i>
      <i class="iconfont icon-shiwu-5"></i>
      <i class="iconfont icon-shiwu-6"></i>
      <i class="iconfont icon-shiwu-7"></i>
      <i class="iconfont icon-shiwu-8"></i>
      <i class="iconfont icon-shiwu-9"></i>
      <i class="iconfont icon-shiwu-10"></i>
      <i class="iconfont icon-shiwu-11"></i>
      <i class="iconfont icon-shiwu-12"></i>
      <i class="iconfont icon-shiwu-13"></i>
      <i class="iconfont icon-cai1"></i>
      <i class="iconfont icon-shiwu"></i>
      <i class="iconfont icon-chuanxiangcai"></i>
      <i class="iconfont icon-shiwu1"></i>
      <i class="iconfont icon-sw-xc"></i>
      <i class="iconfont icon-beijing"></i>
      <i class="iconfont icon-shiwu2"></i>
      <i class="iconfont icon-shiwu-roudanlei"></i>
      <i class="iconfont icon-shiwu-shucailei"></i>
      <i class="iconfont icon-shiwu3"></i>
      <i class="iconfont icon-cai"></i>
      <i class="iconfont icon-segao"></i>
      <i class="iconfont icon-chuancai"></i>
      <i class="iconfont icon-shiwumiantiao"></i>
      <i class="iconfont icon-jiaozi"></i>
      <i class="iconfont icon-shiwu-canpan"></i>
      <i class="iconfont icon-baozi"></i>
      <i class="iconfont icon-shiwu-"></i>
      <i class="iconfont icon-shiwu-1"></i>
      <i class="iconfont icon-shiwu-2"></i>
      <i class="iconfont icon-shiwu-3"></i>
      <i class="iconfont icon-shiwu-4"></i>
      <i class="iconfont icon-shiwu-5"></i>
      <i class="iconfont icon-shiwu-6"></i>
      <i class="iconfont icon-shiwu-7"></i>
      <i class="iconfont icon-shiwu-8"></i>
      <i class="iconfont icon-shiwu-9"></i>
      <i class="iconfont icon-shiwu-10"></i>
      <i class="iconfont icon-shiwu-11"></i>
      <i class="iconfont icon-shiwu-12"></i>
      <i class="iconfont icon-shiwu-13"></i>
      <i class="iconfont icon-cai1"></i>
      <i class="iconfont icon-shiwu"></i>
      <i class="iconfont icon-chuanxiangcai"></i>
      <i class="iconfont icon-shiwu1"></i>
      <i class="iconfont icon-sw-xc"></i>
      <i class="iconfont icon-beijing"></i>
      <i class="iconfont icon-shiwu2"></i>
      <i class="iconfont icon-shiwu-roudanlei"></i>
      <i class="iconfont icon-shiwu-shucailei"></i>
      <i class="iconfont icon-shiwu3"></i>
      <i class="iconfont icon-cai"></i>
      <i class="iconfont icon-segao"></i>
      <i class="iconfont icon-chuancai"></i>
      <i class="iconfont icon-shiwumiantiao"></i>
      <i class="iconfont icon-jiaozi"></i>
      <i class="iconfont icon-shiwu-canpan"></i>
      <i class="iconfont icon-baozi"></i>
      <i class="iconfont icon-shiwu-"></i>
      <i class="iconfont icon-shiwu-1"></i>
      <i class="iconfont icon-shiwu-2"></i>
      <i class="iconfont icon-shiwu-3"></i>
      <i class="iconfont icon-shiwu-4"></i>
      <i class="iconfont icon-shiwu-5"></i>
      <i class="iconfont icon-shiwu-6"></i>
      <i class="iconfont icon-shiwu-7"></i>
      <i class="iconfont icon-shiwu-8"></i>
      <i class="iconfont icon-shiwu-9"></i>
      <i class="iconfont icon-shiwu-10"></i>
      <i class="iconfont icon-shiwu-11"></i>
      <i class="iconfont icon-shiwu-12"></i>
      <i class="iconfont icon-shiwu-13"></i>
      <i class="iconfont icon-cai1"></i>
      <i class="iconfont icon-shiwu"></i>
      <i class="iconfont icon-chuanxiangcai"></i>
      <i class="iconfont icon-shiwu1"></i>
      <i class="iconfont icon-sw-xc"></i>
      <i class="iconfont icon-beijing"></i>
      <i class="iconfont icon-shiwu2"></i>
      <i class="iconfont icon-shiwu-roudanlei"></i>
      <i class="iconfont icon-shiwu-shucailei"></i>
      <i class="iconfont icon-shiwu3"></i>
      <i class="iconfont icon-cai"></i>
    </div>
    <div class="homeMain">

    </div>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
// import 'swiper/swiper-bundle.css'
import 'swiper/css/swiper.css'
export default {
  name:'HomeMain',
  components:{
    Swiper,
    SwiperSlide
  },
  data(){
    return {
      swiperOption: {
        autoplay:true,
        loop: true,
        effect:'coverflow',
        slidesPerView: 4,
        centeredSlides: true,
        coverflowEffect: {
          rotate: 35,
          stretch: 15,
          depth: 60,
          modifier: 2,
          slideShadows : false
        },
        pagination: {
          el: '.swiper-pagination',
          clickable :true
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        }
      },
    }
  }
}
</script>

<style lang="scss" scoped>
@import '@/assets/scss/basic.scss';
.homeMain{
  background-color: rgb(243, 243, 243);
  .homeTop{
    height: 70px;
    background-color: rgb(224, 224, 224);
    .searchContainer{
      float: right;
      width: 300px;
      height: 40px;
      line-height: 40px;
      border: 1px solid $colorI;
      background-color: #ffffff;
      margin: 13px 75px;
      input {
        width: 240px;
        height: 40px;
        outline: none;  
        border: none;
        font-size: 16px;
        border-right: 1px solid $colorI;
        margin-left: 10px;
      }
      a{
        float: right;
        height: 40px;
        line-height: 40px;
        margin: 2px 7px;
      }
      .iconfont{
        margin: 0 auto;
        font-size: 30px;
      }
    }
  }
  .container{
    width: 1900px;
    .swiper-container{
      height: 300px;
      .swiper-button-prev .swiper-button-next{
        color: chocolate;
      }
      img{
        width: 500px;
        height: 300px;
      }
    }
  }
  .showBar{
    .iconfont{
      font-size: 20px;
    }
  }
  .homeMain{
    height: 500px;
  }
}
</style>