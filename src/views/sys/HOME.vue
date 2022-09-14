<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
    <header>
        <RouterLink to="./HomeView">HomeView</RouterLink>
        <RouterLink to="./about">AboutView</RouterLink>
    </header>
    <div>
        <RouterView></RouterView>
    </div>
    <footer>
      
    </footer>
    

</template>