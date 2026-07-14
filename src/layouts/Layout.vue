<template>
  <div>
    <Header />

    <div class="flex flex-col md:flex-row">
      <Sidebar />

      <main class="flex-1 p-6">
        <slot />
      </main>
    </div>
  </div>
</template>

<script setup>
import Header from '../components/Header.vue'
import Sidebar from '../components/Sidebar.vue'
</script>