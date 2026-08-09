<script setup>
useHead({
  title: 'Inicio',
  meta: [
    {
      name: 'description',
      content: 'Página de inicio del portafolio personal de Andrea Carrillo.'
    }
  ]
})
</script>

<template>
  <main>
    <h1>Portafolio personal</h1>

    <p>Hola, soy Andrea Carrillo.</p>

    <p>
      Este sitio presenta información sobre mí, mis proyectos,
      medios de contacto y publicaciones.
    </p>

    <h2>Secciones</h2>

    <ul>
      <li><NuxtLink to="/sobre-mi">Sobre mí</NuxtLink></li>
      <li><NuxtLink to="/proyectos">Proyectos</NuxtLink></li>
      <li><NuxtLink to="/contacto">Contacto</NuxtLink></li>
      <li><NuxtLink to="/blog">Blog</NuxtLink></li>
    </ul>
  </main>
</template>