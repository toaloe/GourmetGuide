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
    </div>
    <div class="homeMain">
        <div class="left">
          <div class="dishesType">
            <div class="leftTitle1">舌尖上的中国</div>
            <div class="leftTitle2">川菜</div>
          </div>
          <div class="leftTitle3">一菜一格，百菜百味；清鲜醇浓，麻辣辛香</div>
          <div class="divide"></div>
          <div class="history">
            <p>川菜起源于春秋战国时的蜀国，秦汉时期初现端倪，汉晋时期古典川菜成型，以“尚滋味”、“好辛香（指花椒与蜀姜的味道）”为其特点。
              唐宋时期的古典川菜进一步发展，古典川菜出川，“川食店”遍及都城开封和临安，以其“物无定味，适口者珍”的风味特色而赢得众多食客青睐，
              川菜作为一个独立的菜系在两宋时期形成。
              </p>
              <p>
                四川人自古以来便有“尚滋味”的传统，加之川中物产丰富，鸟兽禽鱼为川菜提供了丰富的原料，而大量使用的蜀姜、川花椒等调料，早在汉代就
                作为川人“好辛香”的特征驰名海内，这个“辛香”指的是花椒与蜀姜的味道而不是辣椒。
              </p>
              <p>
                明清时期，川菜进一步发展，直至民国时期，由于明清时期辣椒的传入，近代川菜最终形成“一菜一格，百菜百味”、“清鲜醇浓，麻辣辛香”的特点，
                并发展成为中国菜的第一菜系。
              </p>
          </div>
          <div class="classic">
            <div class="claDivide1"></div>
            <div class="cla1">经</div>
            <div class="cla1">典</div>
            <div class="cla1">菜</div>
            <div class="cla1">品</div>
            <div class="claDivide2"></div>
          </div>
          <div class="classicList">
            <p>川菜即四川地区的菜肴，是中国传统四大菜系之一，也是最有特色的菜系，民间最大菜系，同时被冠以“百姓菜”。</p>
            <p>起源于四川地区，以麻、辣、鲜、香为特色。川菜原料多选家常食材，宴客偶用山珍、江鲜。善用小炒、干煸、干烧和泡、
              烩等烹调法。以“味”闻名，味型较多，富于变化，以鱼香、红油、怪味、麻辣较为突出。川菜的风格朴实而又清新，具有浓厚的
              乡土气息。著名代表菜品有：东坡肘子、冷锅鱼、石磨豆花、甜皮鸭、卤鸭子、鱼香肉丝、回锅肉、麻婆豆腐、辣子鸡、酸菜鱼、
              水煮鱼、毛血旺、夫妻肺片、重庆火锅开水白菜、过桥排骨、等等。
            </p>
            <p>
              在国际上享有“食在中国，味在四川”的美誉；其中最负盛名的菜肴有：干烧岩鲤、干烧桂鱼、鱼香肉丝、廖排骨、怪味鸡、宫保鸡丁、
              五香卤排骨、粉蒸牛肉、麻婆豆腐、毛肚火锅、干煽牛肉丝、灯影牛肉、担担面、赖汤圆、龙抄手等；川菜中六大名菜是：鱼香肉丝、
              宫保鸡丁、夫妻肺片、麻婆豆腐、回锅肉、东坡肘子、开水白菜等。
            </p>
          </div>
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
    width: 100%;
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
      width: 25%;
      height: 1000px;
      -webkit-box-shadow: 0 0 100px $colorJ inset;
      .dishesType{
        width: 100%;
        display: inline-block;
        height: 50px;
        line-height: 50px;
        .leftTitle1{
          float: left;
          font-size: 20px;
          font-weight: bold;
          margin-left: 70px;
          color: rgb(65, 8, 8);
        }
        .leftTitle2{
          float: right;
          font-family: FangSong_GB2312;
          font-size: 40px;
          color: rgb(65, 8, 8);
          font-weight: bolder;
          margin-right: 100px;
        }
      }
      .divide{
        width: 80%;
        margin-left: 26px;
        border-top: 1px solid rgb(151, 22, 108);
        margin-top: 10px;
      }
      .history{
        width: 78%;
        margin-left: 33px;
        font-size: 17px;
      }
      .classic{
        text-align: center;
        margin-top: 5px;
        .claDivide1{
          display: inline-block;
          height: 1px;
          width: 70px;
          background-color: rgb(65, 8, 8);
          margin-bottom: 8px;
        }
        .cla1{
          display: inline-block;
          width: 45px;
          height: 45px;
          line-height: 45px;
          font-size: 23px;
          font-weight: bold;
          border: 4px solid rgb(65, 8, 8);
          border-radius: 50%;
          text-align: center;
        }
        .claDivide2{
          display: inline-block;
          height: 1px;
          width: 70px;
          background-color: rgb(65, 8, 8);
          margin-right: 50px;
          margin-bottom: 8px;
        }
      }
      .classicList{
        font-size: 17px;
        margin: 5px 25px 10px 12px;
      }
      .leftTitle3{
        font-size: 18px;
        font-family: youyuan;
        font-weight: bold;
        margin-left: 50px;
        }
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
      width: 65%;
      height: 1000px;
      float: left;
      // background-color: blue;
      -webkit-box-shadow: 0 0 10px $colorJ inset

    }
  }
}
</style>