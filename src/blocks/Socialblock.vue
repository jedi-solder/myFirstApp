<template>
  <div class="social">
    <p class="social__text">Nunc eget nibh</p>
    <h1 class="social__title">Morbi in nisl auctor</h1>
    <Sociallinks></Sociallinks>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Sociallinks from '@/components/Sociallinks';

export default {
  name: 'Socialblock',
  components: { Sociallinks },
};
</script>

<style>
.social {
  width: 100vw;
  background-image: url(../assets/img/main_image.png);
  background-size: cover;
  display: grid;
  grid-template-rows: 300px repeat(3, 100px) 125px;
}
.social__text {
  grid-row-start: 2;
  color: #ffffff;
  font-size: 18px;
  font-weight: 400;
  font-style: normal;
  letter-spacing: normal;
  line-height: 48px;
}
.social__text::after{
  content: "";
  width: 12%;
  border-bottom: 2px solid white;
  position: absolute;
  top: 370px;
  left: 44%;
}
.social__title {
  grid-row-start: 3;
  color: #ffffff;
  font-size: 60px;
  font-weight: 500;
  font-style: normal;
  letter-spacing: normal;
  line-height: 48px;
}
</style>
