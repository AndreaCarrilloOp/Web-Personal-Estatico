<!-- app/pages/blog.vue -->
<script setup>
useHead({
  title: 'Blog',
  meta: [
    { name: 'description', content: 'Publicaciones del blog del portafolio personal.' }
  ]
})
</script>

<template>
  <main>
    <h1>Blog</h1>
    <h2>Rutas automáticas en Nuxt</h2>
    <p>Nuxt genera rutas a partir de los archivos ubicados en app/pages.</p>
    <h2>Navegación con NuxtLink</h2>
    <p>NuxtLink permite navegar entre las páginas internas del sitio.</p>
  </main>
</template>
