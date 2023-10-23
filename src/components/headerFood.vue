<template>
  <header class="header">
    <a href="#">
      <img src="../img/omnifood-logo.png" class="logo" alt="omnifood-logo" />
    </a>
    <nav class="main-nav" :class="{ 'nav-mobile': isMobileNavOpen }">
      <ul class="main-nav-list">
        <li :class="{ 'custm': !isCustm }"><div class="bic"><img src="../img/gallery/gallery-9.jpg" alt=""></div></li>
        <li><a href="#how">How it works</a></li>
        <li><a href="#meals">Meals</a></li>
        <li><a href="#testimonial">Testimonials</a></li>
        <li><a href="#price">Pricing</a></li>
        <li><a class="last" href="#cta">Try for free</a></li>
      </ul>
    </nav>
    <button class="btn-mobile-nav" @click="toggleMobileNav">
      <ion-icon class="icon-mobile-nav" :class="{ 'not': isMobileNavOpen }" name="menu-outline" style="visibility: visible !important;"></ion-icon>
      <ion-icon class="icon-mobile-nav" :class="{ 'not': !isMobileNavOpen }"  name="close-outline" style="visibility: visible !important;"></ion-icon>
    </button>
  </header>
</template>

<script>
export default {
  name: 'header', 
  data(){
    return {
      isMobileNavOpen: false,
      isCustm: false
    }
  },
  methods: {
    toggleMobileNav(){
      this.isMobileNavOpen = !this.isMobileNavOpen;
      this.isCustm = !this.isCustm;
    }
  }
}
</script>