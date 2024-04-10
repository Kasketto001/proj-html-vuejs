<template>
    <footer>
         <div class="container-large mx-3">
             <div class="row gap-5">
                 <div class="col d-flex flex-column gap-3">
                     <img :src="logoSrc" alt="">
                     <p>{{ description }}</p>
                 </div>
                 <div class="col">
                     <h4>{{ quickLinksTitle }}</h4>
                     <div class="spacing d-flex gap-2 my-3">
                         <div class="green spacing2"></div>
                         <div class="green spacing"></div>
                     </div>
 
                     <ol>
                         <li v-for="link in quickLinks" :key="link">{{ link }}</li>
                     </ol>
                 </div>
                 <div class="col">
                     <h4>{{ contactTitle }}</h4>
                     <div class="spacing d-flex gap-2 my-3">
                         <div class="green spacing2"></div>
                         <div class="green spacing"></div>
                     </div>
 
                     
                     <ol>
                         <li v-for="contactInfo in contactDetails" :key="contactInfo">{{ contactInfo }}</li>
                     </ol>
 
 
                 </div>
                 <div class="col">
                     <h4>{{ mapLocationTitle }}</h4>
                     <div class="spacing d-flex gap-2 my-3">
                         <div class="green spacing2"></div>
                         <div class="green spacing"></div>
                     </div>
                     <img class="map" :src="mapSrc" alt="">
                 </div>
             </div>
         </div>
         <div class="pre-navbar d-flex justify-content-between py-5 px-5">
             <div class="content-left d-flex gap-2 align-items-center justify-content-center">
                 <span>{{ copyrightText }}</span>
             </div>
             <div class="content-right align-items-center d-flex gap-4">
                 <i class="fa-brands fa-facebook-f"></i>
                 <i class="fa-brands fa-x-twitter"></i>
                 <i class="fa-brands fa-pinterest-p"></i>
             </div>
         </div>
    </footer>
 </template>
 
 <script>
 export default {
     name: 'AppFooter',
     props: {
         logoSrc: String,
         description: String,
         quickLinksTitle: String,
         quickLinks: Array,
         contactTitle: String,
         contactDetails: Array,
         mapLocationTitle: String,
         mapSrc: String,
         copyrightText: String
     }
 }
 </script>
 
 <style>
 /* eventuali stili CSS possono essere aggiunti qui */
 </style>
 