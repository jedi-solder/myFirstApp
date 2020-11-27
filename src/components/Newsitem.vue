<template>
  <div class="news__wrap">
    <div class="news__date">
      <p class="day">15</p>
      <p class="month">September</p>
      <p class="year">2016</p>
    </div>
    <div class="news__text">
      <h3 class="news__text-head">Fugiat Quo Voluptas</h3>
      <div class="news__text-main">Quis autem vel eum iure reprehenderit qui in ea voluptate
        velit esse.</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Newsitem',
};
</script>

<style scoped>
.news__wrap {
  width: 100%;
  display: flex;
  justify-content: space-around;
  padding: 20px;
}
.news__date {
  width: 100px;
  height: 140px;
  border-radius: 49px;
  border: 1px solid #e8e8e8;
  background-color: #f7f7f7;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.news__date p {
  padding: 0;
  margin: 0;
  display: block;
}
.news__text {
  max-width: 310px;
  text-align: left;
}
.news__text-head {
  color: #f44336;
  font-size: 16px;
  font-weight: bold;
  font-style: normal;
  letter-spacing: normal;
  line-height: 48px;
}
.news__text-main {
  color: #9e9e9e;
  font-size: 14px;
  font-weight: 300;
  font-style: normal;
  letter-spacing: normal;
  line-height: 24px;
  text-align: left;
}
.day {
  color: #000000;
  font-size: 32px;
  font-weight: 500;
}
.month {
  color: #9e9e9e;
  font-size: 14px;
  font-weight: 500;
  line-height: 28px;
}
.year {
  color: #9e9e9e;
  font-size: 13px;
  font-weight: 400;
  font-style: italic;
  line-height: 20px;
}
</style>
