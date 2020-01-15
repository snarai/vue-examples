<template>
  <div class="ds-btn-cash">
    <a href="javascript:void()">今すぐ購入</a>
  </div>
</template>

<script>
export default {
  name: "BuyButton"
};
</script>

<style scoped>
.ds-btn-cash {
  width: 216px;
  height: 52px;
  display: block;
  margin: 0 auto 6px;
  box-sizing: border-box;
  border-bottom: 2px solid transparent;
  border-radius: 3px;
  border-bottom-color: #d5720c;
  background-color: #ff8b12;
  line-height: 52px;
  position: relative;
  opacity: 1;
  text-align: center;
  cursor: pointer;
}
.ds-btn-cash a {
  color: #fff !important;
  font-size: 20px;
  font-weight: bold;
  text-decoration: none;
}
</style>