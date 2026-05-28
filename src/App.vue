<template>
<nav>
  <div class="nav-logo">Julio Martínez</div>
  <ul class="nav-links">
    <li><a href="#sobre-mi">Sobre mí</a></li>
    <li><a href="#proyectos">Proyectos</a></li>
    <li><a href="#saas">En construcción</a></li>
    <li><a href="#contacto">Contacto</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero" id="inicio">
  <div class="hero-content">
    <div class="hero-eyebrow">Frontend Developer</div>
    <h1 class="hero-title">
      Construyo interfaces que <em>funcionan</em> en producción
    </h1>
    <p class="hero-desc">
      Proyectos reales para clientes reales — Vue, Nuxt, React, Shopify y WordPress. Basado en Valencia, disponible para trabajo remoto.
    </p>
    <div class="hero-cta">
      <a href="#proyectos" class="btn-primary">Ver proyectos</a>
      <a href="#contacto" class="btn-outline">Contactar</a>
    </div>
  </div>

  <div class="hero-visual">
    <div class="hero-stat-card">
      <div class="stat-label">Stack principal</div>
      <div class="stat-value">Vue · Nuxt · React</div>
      <div class="stack-chips">
        <span class="chip">TypeScript</span>
        <span class="chip">Tailwind</span>
        <span class="chip">Pinia</span>
        <span class="chip">Vite</span>
        <span class="chip">Vitest</span>
      </div>
    </div>
    <div class="hero-stat-card">
      <div class="stat-label">Ecosistemas</div>
      <div class="stat-value">Shopify · WordPress</div>
      <div class="stack-chips">
        <span class="chip">Liquid</span>
        <span class="chip">PHP</span>
        <span class="chip">Strapi</span>
        <span class="chip">REST APIs</span>
      </div>
    </div>
    <div class="hero-stat-card">
      <div class="stat-label">Actualmente construyendo</div>
      <div class="stat-value">SaaS · Hostelería</div>
      <div class="stat-sub">Fastify · PostgreSQL · Node.js</div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="sobre-mi">
  <div class="section-label">Sobre mí</div>
  <div class="about-grid">
    <div>
      <h2 class="section-title">Developer freelance con proyectos<br>desplegados en producción</h2>
      <div class="about-text">
        <p>Llevo tiempo entregando proyectos reales a clientes — desde sitios corporativos hasta plataformas e-commerce con CMS headless. No tengo proyectos de práctica que nunca vio nadie: tengo código que está corriendo en producción ahora mismo.</p>
        <p>Me muevo con comodidad entre <span class="about-highlight">Vue/Nuxt, React, Shopify y WordPress</span>. Sé que cada ecosistema tiene sus convenciones y las respeto. También configuré y desplegué backends en Strapi Cloud cuando el proyecto lo requería.</p>
        <p>Actualmente ampliando hacia backend con <span class="about-highlight">Fastify y PostgreSQL</span>, aplicado en un SaaS propio para el sector hostelero que nació de un problema real que vi de primera mano.</p>
      </div>
    </div>
    <div>
      <div class="section-label" style="margin-bottom:1.5rem">Tech stack</div>
      <div class="skills-grid">
        <div class="skill-item">
          <div class="skill-name">Vue 3 / Nuxt 3</div>
          <div class="skill-type">Frontend · SSR</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">React 18</div>
          <div class="skill-type">Frontend · SPA</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">TypeScript</div>
          <div class="skill-type">Tipado estático</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">Tailwind CSS</div>
          <div class="skill-type">Estilos</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">Shopify / Liquid</div>
          <div class="skill-type">E-commerce</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">WordPress / PHP</div>
          <div class="skill-type">CMS · Temas custom</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">Strapi Cloud</div>
          <div class="skill-type">CMS headless</div>
        </div>
        <div class="skill-item">
          <div class="skill-name">Vitest</div>
          <div class="skill-type">Testing</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="proyectos">
  <div class="section-label">Proyectos</div>
  <h2 class="section-title">Trabajo real,<br>clientes reales</h2>
  <div class="projects-grid">

    <a class="project-card featured" href="https://github.com/JulioMartinezTech/mundoelectrico-nuxt" target="_blank">
      <div>
        <span class="project-badge">Proyecto estrella</span>
        <div class="project-tag">Plataforma web · CMS headless</div>
        <div class="project-name">Mundo Eléctrico</div>
        <div class="project-desc">Plataforma con SSR para tienda del sector eléctrico. Frontend en Nuxt 3 con TypeScript y Pinia, consumiendo una API REST de Strapi que configuré y desplegué en Strapi Cloud.</div>
        <div class="project-stack">
          <span class="project-tech">Nuxt 3</span>
          <span class="project-tech">TypeScript</span>
          <span class="project-tech">Pinia</span>
          <span class="project-tech">Tailwind</span>
          <span class="project-tech">Strapi Cloud</span>
        </div>
        <span class="project-link">Ver en GitHub</span>
      </div>
      <div>
        <div style="background:var(--navy-light);padding:2rem;border:1px solid rgba(201,168,76,0.1)">
          <div style="font-size:0.7rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--text-muted);margin-bottom:1rem">Arquitectura</div>
          <div style="display:flex;flex-direction:column;gap:0.75rem">
            <div style="padding:0.75rem;background:rgba(201,168,76,0.06);border-left:2px solid var(--gold);font-size:0.8rem;color:var(--cream)">Nuxt 3 · Vercel</div>
            <div style="text-align:center;color:var(--text-muted);font-size:0.7rem">↕ REST API</div>
            <div style="padding:0.75rem;background:rgba(201,168,76,0.06);border-left:2px solid var(--gold-dim);font-size:0.8rem;color:var(--cream)">Strapi Cloud</div>
          </div>
        </div>
      </div>
    </a>

    <a class="project-card" href="https://github.com/JulioMartinezTech/departlite-theme" target="_blank">
      <div class="project-tag">E-commerce · Shopify</div>
      <div class="project-name">departlite theme</div>
      <div class="project-desc">Tema Shopify personalizado sobre Online Store 2.0 para tienda en producción. Secciones configurables, soporte multiidioma y Theme Check integrado.</div>
      <div class="project-stack">
        <span class="project-tech">Shopify</span>
        <span class="project-tech">Liquid</span>
        <span class="project-tech">Theme Check</span>
      </div>
      <span class="project-link">Ver en GitHub</span>
    </a>

    <a class="project-card" href="https://www.mshinteriorismo.com" target="_blank">
      <div class="project-tag">Web corporativa · Desplegada</div>
      <div class="project-name">MSH Interiorismo</div>
      <div class="project-desc">Sitio corporativo para estudio de interiorismo, en producción con dominio propio. Formulario de contacto funcional vía EmailJS e integración con Instagram.</div>
      <div class="project-stack">
        <span class="project-tech">Vue 3</span>
        <span class="project-tech">Vue Router</span>
        <span class="project-tech">EmailJS</span>
      </div>
      <span class="project-link">Ver sitio en vivo</span>
    </a>

    <a class="project-card" href="https://github.com/JulioMartinezTech/Asopropird" target="_blank">
      <div class="project-tag">WordPress · PHP</div>
      <div class="project-name">Asopropird</div>
      <div class="project-desc">Tema WordPress a medida para asociación sin fines de lucro. Plantillas custom por sección — membresías, directorio de aliados, perfiles de empresa.</div>
      <div class="project-stack">
        <span class="project-tech">WordPress</span>
        <span class="project-tech">PHP</span>
        <span class="project-tech">CSS</span>
      </div>
      <span class="project-link">Ver en GitHub</span>
    </a>

  </div>
</section>

<!-- SAAS -->
<section class="saas" id="saas">
  <div class="saas-inner">
    <div>
      <div class="saas-status">
        <div class="saas-dot"></div>
        En construcción activa
      </div>
      <h2 class="saas-title">SaaS de inventario<br>para hostelería</h2>
      <p class="saas-desc">Nació de un problema real: el inventario de un restaurante se hacía en papel y se enviaba por foto de WhatsApp. Construí una primera versión que ya está en uso, y ahora la estoy convirtiendo en un producto completo.</p>
      <ul class="saas-features">
        <li>Conteo periódico adaptado al ritmo de cocina — sin registrar cada movimiento</li>
        <li>Órdenes de compra y gestión de proveedores</li>
        <li>Cálculo automático de merma real</li>
        <li>Generación de informes en PDF</li>
      </ul>
    </div>
    <div>
      <div class="hero-stat-card" style="margin-bottom:1rem">
        <div class="stat-label">Backend</div>
        <div class="stat-value">Fastify · PostgreSQL</div>
        <div class="stat-sub">Node.js · REST API</div>
      </div>
      <div class="hero-stat-card" style="margin-bottom:1rem">
        <div class="stat-label">Frontend</div>
        <div class="stat-value">Vue 3 · TypeScript</div>
        <div class="stat-sub">Pinia · Vitest</div>
      </div>
      <a class="project-card" href="https://github.com/JulioMartinezTech/inventario-app" target="_blank" style="margin-top:0">
        <div class="project-tag">Versión inicial · En uso activo</div>
        <div class="project-name" style="font-size:1rem">inventario-app</div>
        <div class="project-desc" style="margin-bottom:0.75rem">La app original que usa el restaurante hoy. Vue 3 + TypeScript + Vitest.</div>
        <span class="project-link">Ver en GitHub</span>
      </a>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contacto">
  <div class="contact-inner">
    <div class="section-label">Contacto</div>
    <div class="gold-divider"></div>
    <h2 class="contact-title">Hablemos</h2>
    <p class="contact-sub">Disponible para oportunidades remotas. Si tienes un proyecto o una posición que crees que encaja, escríbeme.</p>
    <div class="contact-links">
      <a href="mailto:juliomartineztech@gmail.com" class="contact-link">✉ Email</a>
      <a href="https://www.linkedin.com/in/julio-martínez-723b05156/" target="_blank" class="contact-link">LinkedIn</a>
      <a href="https://github.com/JulioMartinezTech" target="_blank" class="contact-link">GitHub</a>
    </div>
  </div>
</section>

<footer>
  <p>juliomartinez.dev · Valencia, España · Disponible para trabajo remoto</p>
</footer>
</template>
<script>
import './App.css'
</script>
<style scoped>
</style>

