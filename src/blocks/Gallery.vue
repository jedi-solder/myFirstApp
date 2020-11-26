<template>
  <div class="gallery__wrap">
    <div class="container">
      <Headermt title="Our Gallery"></Headermt>
      <div class="goods">
        <Good good_name="ASSASIN’S CREED: Rogue"
              good_img="game_1">
        </Good>
        <Good good_name="TOMB RAIDER"
              good_img="game_2">
        </Good>
        <Good good_name="RYSE: Son Of Rome"
              good_img="game_3">
        </Good>
        <Good good_name="WORLD OF WARCRAFT: Wrath Of The Lich King"
              good_img="game_4">
        </Good>
      </div>
    </div>
  </div>
</template>

<script>
// eslint-disable-next-line import/extensions
import Headermt from '@/components/Headermt';
// eslint-disable-next-line import/extensions
import Good from '@/components/Good';

export default {
  name: 'Gallery',
  components: { Good, Headermt },
};
</script>

<style scoped>
.gallery__wrap {
  padding: 90px 0;
}
.goods {
  padding: 90px 0;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
</style>
