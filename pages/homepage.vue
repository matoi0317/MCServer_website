<template>

<div class="wrapper">
    <div class="wrapper1">
      <div class="SlideshowDiv"><SlideshowDiv></SlideshowDiv></div>
      <div class="SideMenuDiv"><SideMenuDiv></SideMenuDiv></div>
    </div>
    <div class="Updates"><Updates></Updates></div>
    <div class="Member"><Member></Member></div>
</div>
</template>

<script>

import SlideshowDiv from "~/components/SlideshowDiv"
import SideMenuDiv from "~/components/SideMenuDiv"
export default {
  components: {SlideshowDiv, SideMenuDiv}
}
</script>

<style scoped>

.wrapper {
  height: calc(100vh - 50px);
  z-index: 1;
}

.wrapper1{
  display:flex;
  height:100%;
  width:100%;
}
.SlideshowDiv{
  height:100%;
  width:66%;
  background-color:black;
  margin: 0px;
}
.SideMenuDiv{
  height:100%;
  width:34%; 
  /* background-color:red; */
  margin: 0px;
  transition: .5s ease;
}
.SideMenuDiv:hover {
  background-color: #ddd;
}

.Updates{
  float:left;
  height:100%;
  width:100%;
  background-color:blue;
}

.Member {
  float:left;
  height:100%;
  width:100%;
  background-color:pink;
}
</style>
