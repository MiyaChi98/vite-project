<script setup lang="ts">
import SideBar from './components/layout/SideBar.vue';
import NavBar from './components/layout/NavBar.vue';
import Footer from './components/layout/Footer.vue';
import MainContent from './components/layout/MainContent.vue';

</script>

<template>
  <a-flex>
    <SideBar />
    <div> 
      <NavBar />
      <MainContent />
      <Footer />
    </div>
  </a-flex>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
