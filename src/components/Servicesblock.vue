<template>
  <div class="services__section">
    <button class="services__button">
      <img :src="require('../assets/icon/' + button_icon + '.svg')" alt="icon">
    </button>
    <div class="services__text">
      <h3 class="services__text-head">{{ text_title }}</h3>
      <p>Itaque earum rerum hic tenetur a sapiente delectus, ut aut
        reiciendis voluptatibus maiores alias consequatur aut
        perferendis doloribus asperiores repellat.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Servicesblock',
  props: ['text_title', 'button_icon'],

};
</script>

<style scoped>
.services__section {
  display: flex;
  text-align: right;
  justify-content: space-between;
  flex-direction: row-reverse;
}
.services__section:nth-child(2n) {
  text-align: left;
  flex-direction: row;
}
.services__text {
  width: 75%;
}
.services__text-head {
  font-size: 16px;
  font-weight: 500;
  font-style: normal;
  letter-spacing: normal;
  line-height: 24px;
  margin-top: 0;
}
p {
  color: #999999;
  font-size: 12px;
  font-weight: 400;
  font-style: normal;
  letter-spacing: normal;
  line-height: 20px;
}
.services__button {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: #e1e1e1;
  border: 1px solid #acacac;
  display: flex;
  justify-content: center;
  align-items: center;
}
.services__button:focus,
.services__button:hover {
  background-color: #f44336;
  outline: none;
  cursor: pointer;
}
.services__button:focus + div h3,
.services__button:hover + div h3 {
  color: #f44336;
}
img {
  width: 25px;
  height: 25px;
}

</style>
