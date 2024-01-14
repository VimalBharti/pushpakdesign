<script setup>
  import VuePdfApp from "vue3-pdf-app";
  import "vue3-pdf-app/dist/icons/main.css";

  const config = {
    toolbar: false
  }
</script>

<template>
  <div class="w-full h-full bg-red-400 border-4" style="height: 100vh;">
    <vue-pdf-app pdf="/files/file_1.pdf" :config="config"></vue-pdf-app>
    <vue-pdf-app pdf="/files/file_2.pdf" :config="config"></vue-pdf-app>
    <vue-pdf-app pdf="/files/file_3.pdf" :config="config"></vue-pdf-app>
    <vue-pdf-app pdf="/files/file_4.pdf" :config="config"></vue-pdf-app>
    <vue-pdf-app pdf="/files/file_5.pdf" :config="config"></vue-pdf-app>
    <vue-pdf-app pdf="/files/file_6.pdf" :config="config"></vue-pdf-app>
  </div>
</template>

<style scoped>

</style>
