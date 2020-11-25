<template>
  <div class="social__linkswrap">
    <a class="social__link"><i class="fab fa-facebook-f"></i></a>
    <a class="social__link"><i class="fab fa-twitter"></i></a>
    <a class="social__link"><i class="fas fa-rss"></i></a>
    <a class="social__link"><i class="fab fa-vk"></i></a>
  </div>
</template>

<script>
export default {
  name: 'Sociallinks',
};
</script>

<style scoped>
.social__linkswrap{
  grid-row-start: 4;
  display: flex;
  justify-content: center;
  align-items: center;
}
.social__link{
  margin: 0 6px;
  width: 38px;
  height: 38px;
  border-radius: 50%;
  border: 2px solid white;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}
</style>
