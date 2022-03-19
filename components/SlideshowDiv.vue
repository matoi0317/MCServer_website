<template>
  <div class="example-3d">
    <swiper class="swiper" :options="swiperOption">
      <swiper-slide class="slide1">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide2">
        <img class = "slide-image" src="/build.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide3">
        <img class = "slide-image" src="/lobby.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide4">
        <img class = "slide-image" src="/test.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide5">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide6">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide7">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide8">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide9">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>
      <swiper-slide class="slide10">
        <img class = "slide-image" src="/athletic.png" />  
        <div class="overlay">
        <div class="text">John Doe</div>  
        </div>
      </swiper-slide>

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
  .overlay {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
  }
  .text {
  background-color: #04AA6D;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
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
    .swiper-slide:hover .slide-image {
      opacity: 0.3;
    }
    .swiper-slide:hover .overlay {
      opacity: 1;
    }
    .swiper-pagination {
      /deep/ .swiper-pagination-bullet.swiper-pagination-bullet-active {
      }
    }
  }
  .slide-image {
    width: 100%;
    height: 100%;
    transition: .5s ease;
  }
</style>