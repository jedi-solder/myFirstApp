<template>
  <div>
    <Socialblock></Socialblock>
    <About></About>
    <Services></Services>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Socialblock from '@/blocks/Socialblock';
// eslint-disable-next-line import/extensions
import About from '@/blocks/About';
// eslint-disable-next-line import/extensions
import Services from '@/blocks/Services';

export default {
  name: 'Home',
  components: {
    Services,
    About,
    Socialblock,
  },
};
</script>
