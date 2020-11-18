<template>
  <a href="#" class="logo">
    <div class="logo__firststring">Historical</div>
    <div class="logo__secondstring">games</div>
  </a>
</template>

<script>
export default {
  name: 'Logo',
};
</script>

<style scoped>
.logo {
  display: block;
  max-width: 180px;
  color: #ffffff;
  font-weight: 500;
  text-decoration: none;
}
.logo__firststring {
  font-size: 36px;
  letter-spacing: 0.77px;
  height: 40px;
  text-align: left;
}
.logo__secondstring {
  font-size: 15px;
  text-transform: uppercase;
  letter-spacing: 30px;
  padding-left: 2px;
}

</style>
