<template>
    
    <Header />
    <NavBar />
    <RouterView>

    </RouterView>
    <Footer />
</template>
  

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import NavBar from './components/NavBar.vue';


</script>

<style scoped>

</style>
