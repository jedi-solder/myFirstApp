<template>
  <nav class="header-navigation">
    <a href="#" class="header-navigation__link header-navigation__link_active">Home</a>
    <a href="#" class="header-navigation__link">About</a>
    <a href="#" class="header-navigation__link">Services</a>
    <a href="#" class="header-navigation__link">Gallery</a>
    <a href="#" class="header-navigation__link">News</a>
    <a href="#" class="header-navigation__link">Team</a>
    <a href="#" class="header-navigation__link">Contact Us</a>
  </nav>
</template>

<script>
export default {
  name: 'Navigation',
};
</script>

<style scoped>
.header-navigation{
  width: inherit;
  height: 80px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid white;
}
.header-navigation__link {
  color: #000000;
  font-size: 17px;
  font-weight: 400;
  letter-spacing: 0.36px;
  text-decoration: none;
  margin: 0 1.2%;
}
.header-navigation__link_active {
  color: white;
}
.header-navigation__link_active::after {
  content: "";
  color: white;
  border-bottom: 3px solid white;
  width: 100px;
  position: absolute;
  bottom: -1px;
}

</style>
