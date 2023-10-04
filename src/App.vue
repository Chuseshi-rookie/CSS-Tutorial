<template lang="ja">
  <div>
    <h1>CSSで実装する簡易的なwebパーツ</h1>
    <h2>～これで君も立派なCSSの魔術師～</h2>
  </div>
    <button class="button">クリックしてみて！</button>
</template>

<script>
import { devtools } from 'vue';

export default {
  name: 'App',
  components: {
    devtools
}
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #474741;
  margin-top: 60px;
}

@font-face {
  font-family: "kanazawa";
  src: url("./fonts/kanazawa-gothic-mini.otf") format("opentype");
  src: url("./fonts/NotoSansJP-.ttf") format("truetype");
}

body {
  background-color: antiquewhite;
}

h1 {
  font-size: 40px;
  font-weight: 700;
  font-family: 'kanazawa';
}

h2 {
  font-size: 30px;
  font-weight: 545;
}

/* ボタンのスタイル */
.button {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.button:hover {
    background-color: #0056b3;
}

</style>
