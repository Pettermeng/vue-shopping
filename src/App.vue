<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/section/Header.vue'
</script>

<template>

  <Header />
  <RouterView />

  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>
</template>

<script>
  export default {
    name: "App",
    components: { 
      Header
    },
    methods: {},
  };
</script>