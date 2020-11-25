<template>
  <form action="#" class="search-form">
    <input type="text" placeholder="Search" class="search-form__input">
    <button class="search-form__btn"><img src="../assets/icon/search.svg" alt="search"></button>
  </form>
</template>

<script>
export default {
  name: 'Search',
};
</script>

<style scoped>
.search-form {
  width: 208px;
  height: 38px;
  border: 1px solid white;
  outline: none;
  display: flex;
  justify-content: space-between;

}
.search-form__input {
  width: 150px;
  height: inherit;
  padding: 0 5px 0 15px;
  background: transparent;
  border: none;
  outline: none;
  color: white;
}
.search-form__input::placeholder {
  color: white;
  font-size: 17px;
  font-weight: 400;
  letter-spacing: 0.36px;
}
.search-form__btn{
  width: 50px;
  height: inherit;
  border-radius: 0;
  outline: none;
  border: none;
  background: transparent;
  border-left: 1px solid white;
  cursor: pointer;
}
img {
  padding-top: 4px;
}
</style>
