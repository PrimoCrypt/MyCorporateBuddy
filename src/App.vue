<script setup>
import NavBar from './components/NavBar.vue'
import PageHeader from './components/PageHeader.vue'
import Items from './components/Items.vue'
</script>

<template>
  <div class="pt-6 px-6 sm:px-14 flex flex-col bg-[#FAFAFA] text-black gap-20">
    <NavBar logo="LOGO" />
    <body class="flex flex-col items-center">
      <PageHeader />
      <Items />
    </body>
  </div>
</template>
