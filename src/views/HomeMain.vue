<template>
  <div class="homeMain">
    <div class="homeTop">
      <div class="searchContainer">
        <input type="text">
        <a href="javaScript:;"></a>
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
      margin: 13px 20px;
      input {
        width: 254px;
        height: 40px;
        outline: none;  
        border: none;
        border-right: 1px solid $colorI;
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
  
}
</style>