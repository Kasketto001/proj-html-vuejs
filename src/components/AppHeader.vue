<script>
export default {
    name: 'AppHeader',
}
</script>

<template>
    <header>
        <div class="pre-navbar d-flex justify-content-between py-2 px-5">
            <div class="content-left d-flex gap-2 align-items-center">
                <span>(001) 88451234</span>
                <span>88455438</span>
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
                <img src="../assets/cropped-Group-39-2x.png" alt="">
              </div>
              <div class="links d-flex gap-3">
                <a href="#">HOME</a>
                <a href="#">ABOUT</a>
                <a href="#">SERVICES</a>
                <a href="#">SHOWCASE</a>
                <a href="#">BLOG</a>
                <a href="#">CONTACT</a>


              </div>
              <div class="actions d-flex gap-4 align-items-center">
                <button class="brand-button px-5 py-3">PURCHASE</button>
                <button class="search-button"><i class="fa-solid fa-magnifying-glass"></i></button>
              </div>
              
            </nav>
        </div>
    </header>
</template>

<style>

</style>
