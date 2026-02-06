<template>
  <div class="landing">
    <div class="landing__content">
      <div class="landing__badge">Próximamente</div>
      <h1 class="landing__title">Julio Martinez</h1>
      <p class="landing__subtitle">Desarrollador de Software & Tech Lead</p>

      <div class="landing__divider"></div>

      <p class="landing__description">
        Estoy construyendo algo increíble. Mientras tanto, puedes revisar mis proyectos actuales o
        contactarme a través de mis redes.
      </p>

      <!-- <div class="landing__social">
        <a href="https://github.com/tu-usuario" target="_blank" class="landing__link -github"
          >GitHub</a
        >
        <a href="https://linkedin.com/in/tu-usuario" target="_blank" class="landing__link -linkedin"
          >LinkedIn</a
        >
        <a href="mailto:hola@juliomartinez.dev" class="landing__link -email">Email</a>
      </div>

      <a href="/inventario" class="landing__btn-app">Ir al Sistema de Inventario →</a> -->
    </div>
  </div>
</template>

<style scoped>
.landing {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: radial-gradient(circle at top right, #1e293b 0%, #0f172a 100%);
  color: white;
  padding: 20px;
  text-align: center;
  font-family: 'Inter', sans-serif;
}

.landing__badge {
  display: inline-block;
  padding: 4px 12px;
  background: rgba(52, 152, 219, 0.2);
  border: 1px solid #3498db;
  color: #3498db;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: bold;
  margin-bottom: 20px;
}

.landing__title {
  font-size: clamp(2.5rem, 8vw, 4rem);
  font-weight: 900;
  letter-spacing: -2px;
  margin: 0;
}

.landing__subtitle {
  font-size: 1.2rem;
  color: #94a3b8;
  margin-top: 10px;
}

.landing__divider {
  width: 60px;
  height: 4px;
  background: #3498db;
  margin: 30px auto;
  border-radius: 2px;
}

.landing__description {
  max-width: 500px;
  line-height: 1.6;
  color: #cbd5e1;
  margin-bottom: 40px;
}

.landing__social {
  display: flex;
  gap: 15px;
  justify-content: center;
  margin-bottom: 30px;
}

.landing__link {
  text-decoration: none;
  color: white;
  font-weight: 600;
  transition: opacity 0.2s;
}

.landing__btn-app {
  display: inline-block;
  margin-top: 20px;
  padding: 12px 24px;
  background: white;
  color: #0f172a;
  border-radius: 8px;
  font-weight: bold;
  text-decoration: none;
  transition: transform 0.2s;
}

.landing__btn-app:hover {
  transform: translateY(-3px);
}
</style>
<style scoped></style>
