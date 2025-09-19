<template>
  <div class="home-container">
    <h1>Welcome to COA Examples App</h1>
    <p>This Nuxt 4 application is configured for Cloudflare Workers deployment.</p>
    
    <div class="navigation">
      <NuxtLink to="/coa-examples" class="nav-link">
        View COA Examples
      </NuxtLink>
    </div>
  </div>
</template>

<script setup lang="ts">
// Set page metadata
useHead({
  title: 'Home - COA Examples App',
  meta: [
    { name: 'description', content: 'COA Examples application built with Nuxt 4 and TypeScript' }
  ]
})
</script>

<style scoped>
.home-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
  font-family: Arial, sans-serif;
}

h1 {
  color: #333;
  margin-bottom: 1rem;
}

p {
  color: #666;
  font-size: 1.1rem;
  margin-bottom: 2rem;
}

.navigation {
  margin-top: 2rem;
}

.nav-link {
  display: inline-block;
  padding: 1rem 2rem;
  background: #00d8ff;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 500;
  transition: background-color 0.3s ease;
}

.nav-link:hover {
  background: #00b8d4;
}
</style>