<script setup>
import NavBar from '@/components/app/NavBar.vue';
import Breadcrumb from '@/components/app/Breadcrumb.vue';
</script>

<template>
  <div class="app-layout">
    <NavBar />
    <main class="main-content">
      <Breadcrumb />
      <router-view />
    </main>
  </div>
</template>

<style scoped>
.app-layout {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}
.main-content {
  flex: 1;
  padding: 2rem;
  max-width: 1440px;
  margin: 0 auto;
  width: 100%;
}
</style>
