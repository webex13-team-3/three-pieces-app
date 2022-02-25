<template>
  <div class="home">
    <div class="left">
      <div class="leftbox">
        <div class="teamname">こんにちは</div>
        <div class="name">
          <p>Satsuki Fukushima</p>
          <p>Miku Akimoto</p>
          <p>EEri Morifuji</p>
        </div>
      </div>
    </div>

    <div class="right">
      <div class="rightbox">
        <p>クイズ</p>
        <p>Vueパレット</p>
        <p>メモ</p>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
.home {
  display: flex;
  width: 100%;
}
.right {
  width: 50%;
  display: flex;
  flex-direction: column;
  text-align: center;
}
.left {
  width: 50%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  text-align: center;
}
.leftbox {
  position: absolute;
  top: 40%;
  left: 30%;
}
.teamname {
  font-size: 30px;
  margin-bottom: 50px;
  font-weight: bold;
}
.name {
  font-size: 20px;
}
.rightbox {
  position: absolute;
  top: 40%;
  left: 60%;
  font-size: 30px;
}
</style>
