<template>
  <div class="newsAndEvents">
    <div class="container">
      <Headermt title="News & Events"></Headermt>
      <div class="newsAndEvents__wrap">
        <div class="news">
          <h2>Latest News</h2>
          <Newsitem></Newsitem>
          <Newsitem></Newsitem>
          <Newsitem></Newsitem>
        </div>
        <div class="events"></div>
      </div>
    </div>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Headermt from '@/components/Headermt';
// eslint-disable-next-line import/extensions
import Newsitem from '@/components/Newsitem';

export default {
  name: 'News',
  components: { Newsitem, Headermt },
};
</script>

<style scoped>
.news,
.events {
  width: 48%;
}

</style>
