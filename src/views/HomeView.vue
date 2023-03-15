<script setup lang="ts">

import HomeViewCardVue from "../components/HomeViewCard.vue"
import HomeBody from "../components/HomeBody.vue";
</script>
<!-- Template-->
<template>
  <main>
    <HomeViewCardVue />
    <HomeBody />
    
  </main>
</template>

<!-- Style-->
<style scoped>
/* main {
  height: 100%;
} */

main {
  display: flex;
  flex-direction: column;
  overflow : auto;
}
</style>