---
layout: page
title: "Hello World"
---

<div class="bg-gradient-to-br from-stone-900 via-stone-800 to-stone-900 px-20 py-20 flex overflow-hidden relative">
  <div class="w-full text-white py-14 relative z-10 text-center">
    <div class="inline-flex rounded-full text-xl border-orange-500 text-orange-500 border-2 pt-1 px-4 mb-6">
      <svg class="h-6 w-6 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
        <path d="M8.4,18.2C8.78,18.7,9,19.32,9,20c0,1.66-1.34,3-3,3s-3-1.34-3-3s1.34-3,3-3c0.44,0,0.85,0.09,1.23,0.26l1.41-1.77 c-0.92-1.03-1.29-2.39-1.09-3.69l-2.03-0.68C4.98,11.95,4.06,12.5,3,12.5c-1.66,0-3-1.34-3-3s1.34-3,3-3s3,1.34,3,3 c0,0.07,0,0.14-0.01,0.21l2.03,0.68c0.64-1.21,1.82-2.09,3.22-2.32l0-2.16C9.96,5.57,9,4.4,9,3c0-1.66,1.34-3,3-3s3,1.34,3,3 c0,1.4-0.96,2.57-2.25,2.91v2.16c1.4,0.23,2.58,1.11,3.22,2.32l2.03-0.68C18,9.64,18,9.57,18,9.5c0-1.66,1.34-3,3-3s3,1.34,3,3 s-1.34,3-3,3c-1.06,0-1.98-0.55-2.52-1.37l-2.03,0.68c0.2,1.29-0.16,2.65-1.09,3.69l1.41,1.77C17.15,17.09,17.56,17,18,17 c1.66,0,3,1.34,3,3s-1.34,3-3,3s-3-1.34-3-3c0-0.68,0.22-1.3,0.6-1.8l-1.41-1.77c-1.35,0.75-3.01,0.76-4.37,0L8.4,18.2z"/>
      </svg>
      Bienvenido a Coderic Hello World
    </div>
    <h1 class="text-6xl font-bold mb-6 mt-2 leading-tight">
      <span class="text-white">Hello World!</span><br>
      <span class="text-orange-500">Coderic Jekyll Theme</span>
    </h1>
    <div class="text-xl mb-8 leading-relaxed text-gray-300 max-w-3xl mx-auto">
      <p class="mb-4">Este es un sitio de demostración usando el tema <strong>jekyll-theme-coderic</strong>.</p>
      <p class="text-lg">El tema proporciona layouts, estilos y componentes reutilizables para el ecosistema Coderic.</p>
    </div>
    <div class="flex gap-4 justify-center">
      <a href="https://github.com/Coderic/jekyll-theme-coderic" class="bg-orange-600 hover:bg-orange-700 text-white font-bold py-3 px-6 rounded-lg text-lg transition-all transform hover:scale-105">
        Ver en GitHub
      </a>
      <a href="/about" class="bg-transparent border-2 border-white hover:bg-white hover:text-stone-900 text-white font-bold py-3 px-6 rounded-lg text-lg transition-all">
        Acerca de
      </a>
    </div>
  </div>
</div>

<section class="bg-white py-16">
  <div class="max-w-screen-xl px-4 mx-auto">
    <div class="text-center mb-12">
      <h2 class="text-4xl font-bold text-stone-800 mb-4">Características del Tema</h2>
      <p class="text-xl text-gray-600 max-w-3xl mx-auto">
        El tema jekyll-theme-coderic incluye todo lo necesario para crear sitios modernos y profesionales.
      </p>
    </div>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white p-8 rounded-lg shadow-lg border-l-4 border-orange-500">
        <div class="text-5xl mb-4">🎨</div>
        <h3 class="text-2xl font-bold text-stone-900 mb-3">Diseño Moderno</h3>
        <p class="text-stone-800">
          Diseño limpio y moderno con Tailwind CSS v4, responsive y accesible.
        </p>
      </div>
      <div class="bg-white p-8 rounded-lg shadow-lg border-l-4 border-orange-500">
        <div class="text-5xl mb-4">⚡</div>
        <h3 class="text-2xl font-bold text-stone-900 mb-3">Fácil de Usar</h3>
        <p class="text-stone-800">
          Configuración simple mediante variables en _config.yml. Sin necesidad de modificar el tema.
        </p>
      </div>
      <div class="bg-white p-8 rounded-lg shadow-lg border-l-4 border-orange-500">
        <div class="text-5xl mb-4">🔧</div>
        <h3 class="text-2xl font-bold text-stone-900 mb-3">Personalizable</h3>
        <p class="text-stone-800">
          Override de layouts e includes para personalizar según tus necesidades.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="bg-stone-50 py-16">
  <div class="max-w-screen-xl px-4 mx-auto">
    <div class="text-center mb-12">
      <h2 class="text-4xl font-bold text-stone-900 mb-6">Cómo Usar el Tema</h2>
    </div>
    <div class="max-w-4xl mx-auto bg-white rounded-lg shadow-lg p-8">
      <h3 class="text-2xl font-bold text-stone-900 mb-4">Instalación</h3>
      <ol class="list-decimal list-inside space-y-4 text-stone-800">
        <li>
          <strong>Agrega el tema a tu Gemfile:</strong>
          <pre class="bg-stone-100 p-4 rounded mt-2 overflow-x-auto"><code>gem "jekyll-remote-theme"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"</code></pre>
        </li>
        <li>
          <strong>Configura _config.yml:</strong>
          <pre class="bg-stone-100 p-4 rounded mt-2 overflow-x-auto"><code>remote_theme: Coderic/jekyll-theme-coderic
title: "Tu Sitio"
navigation:
  - label: "Home"
    url: "/"</code></pre>
        </li>
        <li>
          <strong>Usa el layout en tus páginas:</strong>
          <pre class="bg-stone-100 p-4 rounded mt-2 overflow-x-auto"><code>---
layout: page
title: "Mi Página"
---</code></pre>
        </li>
      </ol>
    </div>
  </div>
</section>
