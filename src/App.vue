<template>
  <div id="app">
    <div class="header-wrap">
      <Header></Header>
      <Navigation></Navigation>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Poppins, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  position: relative;
}

.container {
  max-width: 1170px;
  margin: 0 auto;
}

.header-wrap {
  position: absolute;
  top: 12px;
}
</style>
<script>

// eslint-disable-next-line import/extensions
import Header from '@/blocks/Header';
// eslint-disable-next-line import/extensions
import Navigation from '@/blocks/Navigation';

export default {
  components: {
    Navigation,
    Header,
  },
};
</script>
