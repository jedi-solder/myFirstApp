<template>
  <div>
    <Socialblock></Socialblock>
    <About></About>
    <Services></Services>
    <Gallery></Gallery>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Socialblock from '@/blocks/Socialblock';
// eslint-disable-next-line import/extensions
import About from '@/blocks/About';
// eslint-disable-next-line import/extensions
import Services from '@/blocks/Services';
// eslint-disable-next-line import/extensions
import Gallery from '@/blocks/Gallery';

export default {
  name: 'Home',
  components: {
    Gallery,
    Services,
    About,
    Socialblock,
  },
};
</script>
