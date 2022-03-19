<template>
  <div class="example-3d">
    <swiper class="swiper" :options="swiperOption">
      <swiper-slide class="slide1"><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/build.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/lobby.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/test.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <swiper-slide><img class = "slide-image" src="/athletic.png" /></swiper-slide>
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
  import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
  import 'swiper/css/swiper.css'
  export default {
    name: 'swiper-example-3d-cube',
    title: '3D Cube effect',
    components: {
      Swiper,
      SwiperSlide
    },
    data() {
      return {
        swiperOption: {
          effect: 'cube',
          grabCursor: true,
          loop: true,
          keyboard: {
            enabled: true,
          },
          cubeEffect:{
            shadow:true,
            slideShadows:false,
            shadowOffset:0,
            shadowScale:0,
          }
        }
      }
    }
  }
</script>

<style lang="scss" scoped>

  .example-3d {
    position: relative;
    overflow: hidden;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .swiper {
    width: 600px !important;
    height: 550px;
    position: relative;
    .swiper-slide {
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      font-weight: bold;
      font-size: 12px;
      background-position: 50%;
      background-size: cover;
      color: white;
      border-radius: 20px;
    }
    .swiper-pagination {
      /deep/ .swiper-pagination-bullet.swiper-pagination-bullet-active {
      }
    }
  }
  .slide-image {
    width: 100%;
    height: 100%;
  }
</style>