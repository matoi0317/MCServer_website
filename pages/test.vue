<template>
<html>
  <body>
    <div id="blocks">
      <div id="test">
        <div id="a">aaa</div>
        <div id="b">a</div>
      </div>
      <div id="c">aaa</div>
    </div>
  </body>
</html>
</template>

<script>
</script>

<style scoped>
html, body{
  height:100%;
  width:100%;
  margin:0px;
}
#blocks{
  width:100%;
  height:200%;
  margin:0 auto;
}
#test{
  display:flex;
}
#a{
  /* float:left; */
  height:66.67%;
  width:66%;
  background-color:black;
  margin: 0px;
}
#b{
  /* float:right; */
  height:33.33%;
  width:34%; 
  background-color:red;
  margin: 0px;
}

#c{
  float:left;
  height:100%;
  width:100%;
  background-color:blue;
}
</style>
