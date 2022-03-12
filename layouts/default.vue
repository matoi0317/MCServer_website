<template>
<div class="global-wrapper">
    <div class="global-header">GlobalHeader</div>
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
html, body {
    margin: 0px;
    padding: 0px;
}
</style>
<style scoped>
.global-header {
    height: 50px;
    border-bottom: solid 1px #ddd;
    display: flex;
    align-items: center;
    padding: 0 20px;
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
