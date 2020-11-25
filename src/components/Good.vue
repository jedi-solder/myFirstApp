<template>
  <div class="good">
    <img class="good__image" :src="require('../assets/img/' + good_img + '.jpg')" alt="Good image">
    <div class="good__name">{{ good_name }}</div>
    <button class="good__buy-btn">Buy</button>
  </div>
</template>

<script>
export default {
  name: 'Good',
  props: ['good_name', 'good_img'],
};
</script>

<style scoped>
.good {
  width: 272px;
  height: 482px;
  background-color: #f7f7f7;
}
.good__name{
  color: #000000;
  font-size: 14px;
  font-weight: 500;
  font-style: normal;
  letter-spacing: normal;
  line-height: 24px;
  height: 48px;
  margin-bottom: 5px;
}
.good__buy-btn {
  width: 130px;
  height: 30px;
  background-color: #f44336;
  color: #ffffff;
  font-size: 14px;
  font-weight: 500;
  font-style: normal;
  letter-spacing: normal;
  line-height: 24px;
  border: none;
  outline: none;
}
</style>
