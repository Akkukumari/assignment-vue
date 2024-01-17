<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome :data="childData" />
  </main>
</template>
<script>
const childData = 'Akansha';
</script>

