<template>
  <div class="home">
    <div class="left">
      <div class="leftbox">
        <div class="teamname">原宿ガールズ🍭</div>
      </div>
    </div>

    <div class="right">
      <div class="rightbox">
        <div class="name">
          <p>Satsuki Fukushima</p>
          <p>Miku Akimoto</p>
          <p>Eri Morifuji</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
body {
  background-image: url(../assets/6057300.jpg);
  background-size: cover;
}
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
  left: 28%;
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

  font-weight: bold;
}
p {
  font-family: TsukuARdGothic-Regular;
}
</style>
