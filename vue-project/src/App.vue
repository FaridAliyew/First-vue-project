<template>
  <div>
    <HeroBackground>
      <Navbar />
      <MainHero/>
    </HeroBackground>
    <SamplePromotion/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import HeroBackground from '@/components/HeroBackground.vue';
import MainHero from './components/MainHero.vue';
import SamplePromotion from './components/SamplePromotion.vue';

export default {
  components: {
    Navbar,
    HeroBackground,
    MainHero,
    SamplePromotion
  },
};
</script>

<style>

body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>