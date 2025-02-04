<template>
  <div>
    <!-- <HeroBackground :imageUrl=" require('../images/Image.png')" /> -->
    <Navbar />
    <MainHero/>
  </div>
</template>

<script>
// import HeroBackground from '@/components/HeroBackground.vue';
import Navbar from '@/components/Navbar.vue';
import MainHero from '@/components/MainHero.vue';

export default {
  components: {
    // HeroBackground,
    Navbar,
    MainHero,
  },
  data() {
    return {

    };
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
