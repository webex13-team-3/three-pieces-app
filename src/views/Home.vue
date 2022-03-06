<template>
  <div class="home">
    <div class="left">
      <div class="left-box">
        <h1 class="team-name">原宿ガールズ🍭</h1>
      </div>
    </div>

    <div class="right">
      <div class="right-box">
        <div class="name">
          <p>Satsuki Fukushima</p>
          <p>Miku Akimoto</p>
          <p>Eri Morifuji</p>
        </div>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="container-box">
      <router-link
        to="/"
        class="navigation__link"
        exact-active-class="navigation__link--exact-active"
        >Home</router-link
      >
    </div>
    <div class="container-box">
      <router-link
        to="/quiz"
        class="navigation__link"
        exact-active-class="navigation__link--exact-active"
        >Vue クイズ</router-link
      >
    </div>
    <div class="container-box">
      <router-link
        to="/palette"
        class="navigation__link"
        exact-active-class="navigation__link--exact-active"
        >Vue パレット</router-link
      >
    </div>
    <div class="container-box">
      <router-link
        to="/memo"
        class="navigation__link"
        exact-active-class="navigation__link--exact-active"
        >Vue メモ</router-link
      >
    </div>
  </div>
</template>

<script></script>

<style>
body {
  min-height: 100vh;
  background-image: url(../assets/6057300.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
<style scoped>
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
.left-box {
  position: absolute;
  top: 40%;
  left: 28%;
}
.team-name {
  font-size: 30px;
  margin-bottom: 50px;
  font-weight: bold;
}
.name {
  font-size: 20px;
}
.right-box {
  position: absolute;
  top: 40%;
  left: 60%;
  font-size: 30px;

  font-weight: bold;
}
p {
  font-family: TsukuARdGothic-Regular;
}
.container {
  position: absolute;
  top: 85%;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  left: 0;
}
.container-box {
  text-align: center;
  width: 100%;
  background-color: rgba(241, 182, 182, 0.719);
  height: 200px;
  width: 300px;
  margin: 10px;
  border-radius: 25%;
  font-weight: bold;
}
.navigation__link {
  position: relative;
  top: 50%;
  text-decoration: none;
  font-size: 22px;
  color: black;
  font-family: TsukuARdGothic-Regular;
}
</style>
