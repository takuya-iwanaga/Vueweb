<template>
  <div class="linebot">

    <h1>{{ msg }}</h1>
    <h1><img alt="ganchan" src="@/./assets/ganchan.png" height="70" width="70"></h1>
    <b>ど～も～、ganchanです。ここではやってきたことやすきなことなどをあげていきます。</b>
    <b>主にIT系になりますが気軽にみていってください。詳しい自己紹介は下のリンクをおしてくださ～い！</b>
    <h3>自己紹介</h3>
    <a href="https://vuejs.org">自己紹介</a>
    <h3>やったこと一覧</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">機械学習</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Line bot</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">ハッカソン</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Web</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Unity</a></li>
    </ul>
    <h3>好きなもの一覧</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">youtube</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">ゲーム</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">テクノス</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">株式会社ハックツ</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">音楽</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
b{
  display: inline-block;
  padding: 0;
}
</style>
