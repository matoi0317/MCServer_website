<template>
    <div class="component">
        <div class="title"><span class="under">メンバー紹介</span></div>
        <div class="first">以下の行為が発見された場合、処罰の対象となります。</div>
        <div class="content">
            <div class="text">・Minecraftバニラではできない動きを実現する行為(チートなど)</div>
            <div class="text">・暴言・反社会的発言等、不適切発言</div>
            <div class="text">・チャットガイドラインに違反する行為</div>
            <div class="text">・NULL鯖にとって不利益となる行為</div>
            <div class="text">・不法行為及び、各種規約違反</div>
            <div class="text">・運営のモチベーションを奪う行為</div>
            <div class="text">・その他、運営が不適切と判断した場合</div>
        </div>
        <div class="second">以上がNULL鯖のMinecraftサーバー全体で適用されるルールです。<br>ルールを守り気持ちよく遊べるように心がけてください！</div>
    </div>

</template>

<script>
</script>

<style scoped>
.component{
    width: 80%;
    height: 500px;
    margin: 0 auto;
    position: relative;
}
.title{
    font-size: 30px;
    position: absolute;
    left:10%;
    top:10%;
}

.title:after{
    position: absolute;
  content: " ";
  display: block;
  border-bottom: solid 2px #242525;
  bottom: -20px;
  width: 300%;
}

.content{
    position: absolute;
    top: 40%;
    left: 10%;
}

.text{
    padding: 5px;
}

.first{
    position: absolute;
    top: 30%;
    left: 10%;

}

.second{
    position: absolute;
    top: 95%;
    left: 10%;
}
</style>
