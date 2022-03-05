<template>
<div class="wrapper">
    <div class="wrapper1">
      <div class="SlideshowDiv"><SlideshowDiv></SlideshowDiv></div>
      <div class="SideMenuDiv"><SideMenuDiv></SideMenuDiv></div>
    </div>
    <div class="c">updates</div>
    <div class="d"></div>
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

}
.wrapper1{
  display:flex;
  height:100%;
  width:100%;
}
.SlideshowDiv{
  height:100%;
  width:66%;
  background-color:yellow;
  margin: 0px;
}
.SideMenuDiv{
  height:100%;
  width:34%; 
  /* background-color:red; */
  margin: 0px;
}

.c{
  float:left;
  height:100%;
  width:100%;
  background-color:blue;
}
</style>
