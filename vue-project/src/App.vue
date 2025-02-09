<template>
  <div>
    <HeroBackground>
      <Navbar />
      <MainHero />
    </HeroBackground>
    <SamplePromotion />
    <ProductIntro />
    <AuthForm />
    <!-- <ClientReviews/> -->
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import HeroBackground from '@/components/HeroBackground.vue';
import MainHero from './components/MainHero.vue';
import SamplePromotion from './components/SamplePromotion.vue';
import ProductIntro from './components/ProductIntro.vue';
import AuthForm from './components/AuthForm.vue';
import ClientReviews from './components/ClientReviews.vue';


export default {
  components: {
    Navbar,
    HeroBackground,
    MainHero,
    SamplePromotion,
    ProductIntro,
    AuthForm,
    ClientReviews
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