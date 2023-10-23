<template>
  <header-food></header-food>
  <hero-food></hero-food>
  <featured-food></featured-food>
  <how-food></how-food>
  <meals-food></meals-food>
  <testi-monials></testi-monials>
  <pricing-food></pricing-food>
  <cta-food></cta-food>
  <foot-food></foot-food>
</template>


<script>
import CtaFood from './components/ctaFood.vue'
import FeaturedFood from './components/featuredFood.vue'
import FootFood from './components/footFood.vue'
import HeaderFood from './components/headerFood.vue'
import HeroFood from './components/heroFood.vue'
import HowFood from './components/howFood.vue'
import MealsFood from './components/mealsFood.vue'
import PricingFood from './components/pricingFood.vue'
import TestiMonials from './components/testiMonials.vue'
export default {
  components: { HeroFood, FeaturedFood, HowFood, MealsFood, TestiMonials, PricingFood, CtaFood, FootFood, HeaderFood },
  
}
</script>

<style>
  @import '../src/css/style.css';
  @import '../src/css/general.css';
  @import '../src/css/queries.css';
</style>
