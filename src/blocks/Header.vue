<template>
  <header>
    <div class="container headerContainer">
      <Logo></Logo>
      <Headercontacts></Headercontacts>
      <Search></Search>
    </div>
  </header>
</template>

<script>
// eslint-disable-next-line import/extensions
import Logo from '@/components/Logo';
// eslint-disable-next-line import/extensions
import Headercontacts from '@/components/Headercontacts';
// eslint-disable-next-line import/extensions
import Search from '@/components/Search';

export default {
  name: 'Header',
  components: {
    Search,
    Headercontacts,
    Logo,
  },
};
</script>

<style scoped>
header {
  width: 100%;
  height: 85px;
  background-color: #000000;
  opacity: 0.5;
}
.headerContainer {
  display: flex;
  height: inherit;
  justify-content: space-around;
  align-items: center;
}
</style>
