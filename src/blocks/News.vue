<template>
  <div class="newsAndEvents">
    <div class="container">
      <Headermt title="News & Events"></Headermt>
      <div class="newsAndEvents__wrap">
        <div class="news">
          <h2>Latest News</h2>
        </div>
        <div class="events"></div>
      </div>
    </div>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Headermt from '@/components/Headermt';

export default {
  name: 'News',
  components: { Headermt },
};
</script>

<style scoped>

</style>
