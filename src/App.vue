<template>
  <div id="app">
    <TestComp/> <!-- components:で定義した名前を追加します -->
  </div>
</template>

<script>
import TestComp from "./components/TestComp"; // 作ったVUeファイルのパスと名前に書き換えます。

export default {
  name: "App",
  components: {
    TestComp // importの部分で定義した名前を記述します。
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
