<template>
  <div id="app">
    <AppHeader/>
    <Home/>
    <AppFooter/>
  </div>
</template>

<script setup>
import bootstrap from './assets/css/bootstrap.css'
import all from './assets/css/all.css'
import style from './assets/css/style.css'
import AppHeader from './components/AppHeader.vue'
import Home from './components/Home.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<style>
@import url('https://fonts.gstatic.com');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
</style>