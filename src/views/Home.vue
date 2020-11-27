<template>
  <div>
    <Socialblock></Socialblock>
    <About></About>
    <Services></Services>
    <Gallery></Gallery>
    <Testimonial></Testimonial>
    <News></News>
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
// eslint-disable-next-line import/extensions
import Testimonial from '@/blocks/Testimonial';
// eslint-disable-next-line import/extensions
import News from '@/blocks/News';

export default {
  name: 'Home',
  components: {
    News,
    Testimonial,
    Gallery,
    Services,
    About,
    Socialblock,
  },
};
</script>
