<template>
  <div class="service__wrap">
    <div class="container servicesContainer">
      <Headermt title="Services"></Headermt>
      <div class="servicesBlock__wrap">
        <Servicesblock text_title="Repreh Qui In Ea Voluptate"
                       button_icon="branch">
        </Servicesblock>
        <Servicesblock text_title="Voluptatibus Maiores Alias"
                       button_icon="arrow">
        </Servicesblock>
        <Servicesblock text_title="Aut Perferendis Doloribus"
                       button_icon="dollar">
        </Servicesblock>
        <Servicesblock text_title="Dut Aut Reiciendis Maiores"
                       button_icon="home">
        </Servicesblock>
        <Servicesblock text_title="Maiores Alias Consequatur"
                       button_icon="poll">
        </Servicesblock>
        <Servicesblock text_title="Doloribus Volupta Maiores"
                       button_icon="settings">
        </Servicesblock>
      </div>
    </div>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Headermt from '@/components/Headermt';
// eslint-disable-next-line import/extensions
import Servicesblock from '@/components/Servicesblock';

export default {
  name: 'Services',
  components: {
    Servicesblock,
    Headermt,
  },
};
</script>

<style scoped>
.service__wrap {
  background-color: #f7f7f7;
  padding-top: 90px;
}
.servicesBlock__wrap {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(3, 100px);
  column-gap: 90px;
  row-gap: 75px;
  padding: 90px 0;
}
</style>
