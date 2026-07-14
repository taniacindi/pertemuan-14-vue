<template>
  <Layout>

    <div class="bg-white shadow-lg rounded-xl p-8">

      <h2 class="text-3xl font-bold text-blue-600 mb-4">
        Tentang Aplikasi
      </h2>

      <p class="text-gray-700 mb-3">
        Aplikasi ini dibuat sebagai latihan penggunaan Vue 3
        dengan konsep Layout, Vue Router, dan Tailwind CSS.
      </p>

      <p class="text-gray-700 mb-3">
        Tujuan praktikum ini adalah memahami bagaimana membuat
        struktur tampilan yang konsisten menggunakan Header,
        Sidebar, dan Layout.
      </p>

      <div class="mt-6">

        <h3 class="font-bold text-lg">
          Teknologi yang digunakan
        </h3>

        <ul class="list-disc ml-6 mt-2">
          <li>Vue 3</li>
          <li>Vue Router</li>
          <li>Tailwind CSS</li>
          <li>Vite</li>
        </ul>

      </div>

    </div>

  </Layout>
</template>

<script setup>
import Layout from "../layouts/Layout.vue";
</script>