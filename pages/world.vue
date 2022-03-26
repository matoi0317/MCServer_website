<template>
    <div class="test">
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                みんなでわいわいサバイバル生活ができるよ！
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/lobby.png">
            </div>
            <div class="text">
                NULLサーバーのロビー!すばらしい建築が集まったロビーをぜひご覧ください！
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/test.png">
            </div>
            <div class="text">
                マイクラ初心者から上級者まで楽しく遊べる様々なアスレチックがあります！
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/build.png">
            </div>
            <div class="text">
                自由に建築ができる建築ワールド!建築の練習をするもよし、レッドストーン回路を学ぶもよし、なんでもできる建築ワールド！
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                テストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテスト
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                ここに説明
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                テストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテスト
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                テストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテスト
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                テストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテスト
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="/athletic.png">
            </div>
            <div class="text">
                テストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテストテスト
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style scoped>
html{
    background-color: #f5f5f5;
}

.test{
    width:90%;
    height: calc(100vh - 100px);
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;

}

.box{
    width:25%;
    height:50%;
    background-color: black;
    margin: 3%;
    color:white;
    transition: .5s ease;
}


.box:hover {
    width: 30%;
    height: 55%;
}

.box .content{
    width:90%;
    background-color: red;
    height:50%;
    margin: 0 auto;
    margin-top:5%;
    margin-bottom: 5%;
}

img{
    width:100%;
    height:100%;
}

.box .text{
    margin: 0 auto;
    width:90%;
    text-align: center;
}
</style>
