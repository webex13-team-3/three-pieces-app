<template>
  <h1>Vue クイズ</h1>
  <div class="app">
    <h2>Q. {{ "アブラカタブラの以外な意味とは？" }}</h2>
    <img class="quiz-image" src="" alt="クイズタイトル" />
    <div class="container">
      <button>
        {{ "いただきます" }}
      </button>
      <button>
        {{ "悪霊退散" }}
      </button>
      <button v-on:click="hyouji">
        {{ "花粉症対策" }}
      </button>
    </div>

    <div v-if="seen">{{ "正解！" }}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      seen: false,
    }
  },
  methods: {
    hyouji: function () {
      this.seen = true
    },
  },
}
</script>

<style>
.app {
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.quiz-image {
  height: 300px;
  width: 300px;
  object-fit: contain;
}

.container {
  display: flex;
  height: 2em;
  width: 300px;
  padding: 1em;
  justify-content: space-around;
}
</style>
