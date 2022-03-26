<template>
<div class="global-wrapper">
    <div class="global-header">
      <div class="heading"><h1>NULL</h1></div>
      <div class="menu">
        <a class="active" href="#home">Home</a>
        <a href="#worlds">ワールド</a>
        <a href="#updates">アップデート</a>
        <a href="#rules">ルール</a>
        <a href="#contact">メンバー紹介</a>
</div>
    </div>
    <div class = "right-menu">
      <!-- <button class = 'button menu-button'> Menu </button> -->
      <div class="menu-icon"></div>
      <div class="menu-icon"></div>
      <div class="menu-icon"></div>
      <div class = "menu-items">
          <a href = #about>About</a>
          <a href = #story>Story</a>
          <a href = #notes>Notes</a>
          <a href = #risks>         Risks&Challenges </a>
      </div>
     </div>
    <nuxt />
</div>
</template>
<script></script>
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
  color: grey;
}

.menu a.active {
  background-color: black;
  color: white;
  font-size: 17px;
}

.right-menu {
    margin: 32px;
    font-family: courier;
    position: absolute;
    right: 0;
    display: block;
    z-index: 2;
    width: 50px;
    height:50px;
    border: 1.5px solid black;
    border-radius: 45px;
}

.menu-icon {
  width: 32px;
  height: 5px;
  background-color: black;
  margin: 9px 0 -3px 9px;
}

.menu-items{
  display: none;
  position: absolute;
  right: 10px;
  top: 45px;
  background-color: #f9f9f9;
  min-width: 64px;
  z-index: 1;
  word-wrap: word-break;
}

.menu-items a {
  display: block;
  padding: 16px;
  color: #000;
}

.menu-items a:hover {
  background-color:#000;
  color:#fff;
}

.right-menu:hover .menu-items {
  display: block;
}

.right-menu:hover {
    background-color: #DADADA;
}

.menuButton:hover {
  background-color: #000000;
}
</style>
