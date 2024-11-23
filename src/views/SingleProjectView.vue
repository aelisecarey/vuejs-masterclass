<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
</script>

<template>
  <div>
    <h1>Project {{ route.params?.id }}</h1>
    <div>
      <RouterLink to="/">Home</RouterLink> | <RouterLink to="/projects">Projects</RouterLink>
    </div>
  </div>
</template>
