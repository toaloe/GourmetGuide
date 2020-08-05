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
        <div class="left">
          <h1>{{this.test}}</h1>
        </div>
        <div class="center">
          <div class="menu"  v-for="(item, ind) in menuLists" :key="ind" @click="showDetail(item.value)">
            <div class="menuTitle">{{item.name}}</div>
            <span>{{item.value}}</span>
          </div>
        </div>
        <div class="right">
          <h1>{{this.test}}</h1>
        </div>
    </div>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
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
      menuLists:[
        {
          name:'鲁',
          value:'鲁菜'
        },
        {
          name:'川',
          value:'川菜'
        },
        {
          name:'粤',
          value:'粤菜'
        },
        {
          name:'苏',
          value:'苏菜'
        },
        {
          name:'浙',
          value:'浙菜'
        },
        {
          name:'闽',
          value:'闽菜'
        },
        {
          name:'鲁',
          value:'湘菜'
        },
        {
          name:'徽',
          value:'徽菜'
        }
      ],
      test:''
    }
  },
  methods:{
    showDetail(val){
      console.log(val,"test");
      this.test=val;
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
    height: 1000px;
    .left{
      float: left;
      width: 30%;
      height: 1000px;
      background-color: pink;
    }
    .center{
      float: left;
      width: 10%;
      height: 1000px;
      background-color: $colorH;
      .menu{
        height: 100px;
        border-bottom: 1px solid $colorA;
        .menuTitle{
          display: inline-block;
          width: 60px;
          height: 60px;
          line-height: 60px;
          text-align: center;
          color: $colorJ;
          font-size: 40px;
          font-family: Xingkai SC;
          font-weight: bold;
          border: 3px solid $colorI;
          border-radius: 50%;
          margin: 20px 10px;
        }
        span{
          color: $colorA;
          font-size: 35px;
          margin-left: 10px;
        }
      }
      .menu:hover {
        cursor: pointer;
        background-color: $colorJ;
      }
      .menu:hover .menuTitle{
        color: rgb(27, 95, 27);
        font-size: 35px;
        font-weight: normal;
      }
      .menu:hover span{
        color: $colorH;
        font-size: 45px;
        font-family: YouYuan;
        margin-left: 4px;
        font-weight: bold;
      }
    }
    .right{
      width: 60%;
      height: 1000px;
      float: left;
      background-color: blue;
    }
  }
}
</style>