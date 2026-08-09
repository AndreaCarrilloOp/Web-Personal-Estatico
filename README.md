# Web Personal Estático

[![Nuxt](https://img.shields.io/badge/Nuxt-4.5.2-00DC82?logo=nuxtdotjs&logoColor=white)](https://nuxt.com/)
[![Netlify](https://img.shields.io/badge/Deploy-Netlify-00C7B7?logo=netlify&logoColor=white)](https://web-nuxt.netlify.app/)
[![Status](https://img.shields.io/badge/status-online-success)](https://web-nuxt.netlify.app/)

Sitio web personal estático desarrollado con **Nuxt 4** como parte de una actividad académica de Arquitectura de Información.

## Sitio

**Web desplegada:**  
https://web-nuxt.netlify.app/

## Contenido

El sitio está compuesto por las siguientes páginas:

- Inicio
- Sobre mí
- Proyectos
- Contacto
- Blog

## Implementación

El proyecto aplica los conceptos trabajados en clase:

- Rutas automáticas mediante `app/pages`.
- Navegación interna con `NuxtLink`.
- Layout compartido mediante `app/layouts/default.vue`.
- Componentes reutilizables para encabezado y pie de página.
- Metadatos por página mediante `useHead`.
- Generación de sitio estático.
- Despliegue mediante Netlify.

## Estructura

```text
app/
├── components/
│   ├── TheHeader.vue
│   └── TheFooter.vue
├── layouts/
│   └── default.vue
├── pages/
│   ├── index.vue
│   ├── sobre-mi.vue
│   ├── proyectos.vue
│   ├── contacto.vue
│   └── blog.vue
└── app.vue