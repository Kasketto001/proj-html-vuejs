<template>
  <header>
      <div class="pre-navbar d-flex justify-content-between py-2 px-5">
          <div class="content-left d-flex gap-2 align-items-center">
              <span>{{ phoneNumber1 }}</span>
              <span>{{ phoneNumber2 }}</span>
          </div>
          <div class="content-right align-items-center d-flex gap-4">
              <i class="fa-brands fa-facebook-f"></i>
              <i class="fa-brands fa-x-twitter"></i>
              <i class="fa-brands fa-pinterest-p"></i>
          </div>
      </div>

      <div class="navbar py-3">
          <nav class="d-flex justify-content-between align-items-center mx-4">
            <div class="logo-brand">
              <img :src="logoSrc" alt="">
            </div>
            <div class="links d-flex gap-3">
              <a href="#">{{ homeLink }}</a>
              <a href="#">{{ aboutLink }}</a>
              <a href="#">{{ servicesLink }}</a>
              <a href="#">{{ showcaseLink }}</a>
              <a href="#">{{ blogLink }}</a>
              <a href="#">{{ contactLink }}</a>
            </div>
            <div class="actions d-flex gap-4 align-items-center">
              <button class="brand-button px-5 py-3">{{ purchaseButtonText }}</button>
              <button class="search-button"><i class="fa-solid fa-magnifying-glass"></i></button>
            </div>
            
          </nav>
      </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  props: {
      phoneNumber1: String,
      phoneNumber2: String,
      logoSrc: String,
      homeLink: String,
      aboutLink: String,
      servicesLink: String,
      showcaseLink: String,
      blogLink: String,
      contactLink: String,
      purchaseButtonText: String
  }
}
</script>

<style>
/* eventuali stili CSS possono essere aggiunti qui */
</style>
