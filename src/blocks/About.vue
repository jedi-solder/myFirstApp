<template>
  <div class="container aboutContainer">
    <div class="about__text">
      <Headermt title="About Us!"></Headermt>
      <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit,
        sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
        Neque porro quisquam est, dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.
        Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam,
        nisi ut aliquid ex ea commodi consequatur?</p>
      <p>Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae
        consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
    </div>
    <div class="about__image"><img src="../assets/img/about_img.png" alt="image"></div>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Headermt from '@/components/Headermt';

export default {
  name: 'About',
  components: { Headermt },
};
</script>

<style scoped>
img {
  width: 100%;
}
.aboutContainer{
  width: inherit;
  padding: 80px 0;
  display: flex;
  justify-content: space-between;
}
.about__text,
.about__image {
  width: 48%;
  min-height: 340px;
  text-align: left;
}
p {
  color: #999999;
  font-size: 12px;
  font-weight: 300;
  font-style: normal;
  letter-spacing: normal;
  line-height: 24px;
}
</style>
