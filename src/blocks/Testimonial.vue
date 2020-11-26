<template>
  <div class="testimonial">
    <div class="container">
      <h2>Testimonial</h2>
      <div class="testimonial__slider">
        <button><i class="fas fa-chevron-left"></i></button>
        <div class="testimonial__quote">
          <div class="quote__icon"><i class="fas fa-quote-right"></i></div>
          <div class="quote__text">Donec feugiat tellus sem, laoreet iaculis orci lobortis vel.
            Sed sed luctus orci, at lacinia risus. Ut porttitor ante ac tincidunt elementum.
            Curabitur ex dolor, condimentum vitae nunc vel, pulvinar semper justo.
            Vestibulum et aliquet magna, maximus dapibus enim.
            Vestibulum ex lectus, posuere eu viverra at, mattis et enim. Nam efficitur sem et
            lectus fringilla, at pharetra nulla luctus. Nunc cursus, augue ac ultricies volutpat,
            neque erat congue justo, ac pretium tellus eros a neque. Integer ipsum sem,
            consectetur a mollis ac, cursus eu ipsum.
           </div>
          <div class="quote__author"><span>JOHN SMITH</span> - FOUNDER</div>
        </div>
        <button><i class="fas fa-chevron-right"></i></button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Testimonial',
};
</script>

<style scoped>
.testimonial {
  background-image: url(../assets/img/testimonial_back.png);
  padding: 90px 0;
  color: #ffffff;
  background-position: right top;
  background-size: cover;
  background-color: darkgray;
  background-blend-mode: multiply;
}
h2 {
  font-size: 48px;
  font-weight: 500;
  font-style: normal;
  letter-spacing: normal;
  line-height: 48px;
}
.testimonial__slider{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.testimonial__quote{
  height: 300px;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  width: 85%;
}
.quote__icon{
  opacity: 0.7;
  font-size: 46px;
}
button{
  width: 35px;
  height: 35px;
  background: transparent;
  font-size: 24px;
  font-weight: 300;
  border: 1px solid white;
  color: #ffffff;
}
.quote__text {
  font-size: 14px;
  font-weight: 300;
}
.quote__author{
  font-size: 16px;
  font-weight: 300;
  text-transform: uppercase;
}
.quote__author span {
  font-size: 16px;
  font-weight: 700;
}

</style>
