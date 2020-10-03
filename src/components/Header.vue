<template>

  <header>
    <!-- データを表示させます。-->
    <h1>{{ msg }}</h1>
    <h1><img alt="ganchan" src="@/./assets/ganchan.png" height="70" width="70"></h1>
  </header>
</template>

<script>
export default {
//Vue インスタンスのためのデータオブジェクトです
  data(){
    return{
       msg: "ganchanの部屋 ",
    }
  }
}
</script>

<style>
header{
  background-color: #f6f7f9;
  text-align: center;
  padding: 10px;
}
h1{
  color: #013892;
  margin: 0;
}
p{
  color:#999;
  margin: 0;
}

#app1 {
  background: url("~@/./assets/block.jpg");
  background-size: cover;
  background-position: center;
  width: auto;
  height: auto;
}
</style>
Footer.vue
