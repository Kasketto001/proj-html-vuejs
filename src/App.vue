<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
    name: 'App',
    components: {
        AppHeader, AppMain, AppFooter
    }
}
</script>

<template>
    <AppHeader :phoneNumber1="'(001) 88451234'" :phoneNumber2="'88455438'"
        :logoSrc="'./src/assets/cropped-Group-39-2x.png'" :homeLink="'HOME'" :aboutLink="'ABOUT'"
        :servicesLink="'SERVICES'" :showcaseLink="'SHOWCASE'" :blogLink="'BLOG'" :contactLink="'CONTACT'"
        :purchaseButtonText="'PURCHASE'" />
    <AppMain />
    <AppFooter :logoSrc="'src/assets/cropped-Group-39-2x.png'"
        :description="'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi unde eos accusantium temporibus possimus quaerat dolorum corporis alias, iure itaque, aspernatur laborum fuga expedita dicta ut animi, omnis eligendi et!'"
        :quickLinksTitle="'QUICK LINKS'"
        :quickLinks="['Careers', 'News', 'Terms of use', 'Privacy Projects', 'About', 'Contact']"
        :contactTitle="'CONTACT'"
        :contactDetails="['Patricia C. Amedee 4401 Waldeck Street Grapevine Nashville, TX75051', 'info@yourdomain.com', '+99 (0) 101 0000 888']"
        :mapLocationTitle="'LOCATION ON MAP'" :mapSrc="'src/assets/map.png'"
        :copyrightText="'&copy; BOOLEAN, BUSINESS THEME'" />
</template>

<style></style>
