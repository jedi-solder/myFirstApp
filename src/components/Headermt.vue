<template>
  <h2>{{ title }}</h2>
</template>

<script>
export default {
  name: 'Headermt',
  props: ['title'],
};

</script>

<style scoped>
h2 {
  color: #f44336;
  font-size: 36px;
  font-weight: 500;
  font-style: normal;
  letter-spacing: normal;
}
</style>
