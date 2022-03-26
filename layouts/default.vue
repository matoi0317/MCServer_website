<template>
<div class="global-wrapper">
    <div class="global-header">
      <div class="heading"><h1>NULL</h1></div>
      <div class="menu">
        <a class="active" href="homepage">Home</a>
        <a href="world">ワールド</a>
        <a href="#updates">アップデート</a>
        <a href="rule">ルール</a>
        <a href="homepage #updates">メンバー紹介</a>
      </div>
</div>
    <nuxt />
</div>
</template>
<script>
console.log("hi")
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic&display=swap');
@import url('https://fonts.googleapis.com/css2?family=DotGothic16&family=Zen+Maru+Gothic&display=swap');
html, body {
    margin: 0px;
    padding: 0px;
   font-family: 'DotGothic16', sans-serif;
   /* font-family: 'Zen Maru Gothic', sans-serif; */
}
</style>
<style scoped>
.global-header {
    height: 50px;
    border-bottom: solid 1px #ddd;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    text-align: center;
    overflow: hidden;
    transition: .5s ease;
}
.global-header:hover {
  background-color: black;
  color: white;
}

.global-header:hover a{
  color: white;
}

.global-header:hover a.active{
  background-color: #ddd;
  color: black;
}

.heading {
  position: absolute;
  left: 1%;
}
.menu {
  overflow: hidden;
  display: flex;
  justify-self: flex-end;
  flex-direction: row;
}

.menu a {
  float: right;
  color: black;
  text-align: center;
  padding: 14px 20.5px;
  text-decoration: none;
  font-size: 17px;
  border-left:  1px solid  black;
}

.menu a:hover {
  background-color: #f2f2f2;
  color: black;
}

.menu a.active {
  background-color: black;
  color: white;
  font-size: 17px;
}
</style>