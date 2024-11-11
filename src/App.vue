<script setup>
import NavBar from './components/icons/NavBar.vue';
import DatosPersonales from './components/DatosPersonales.vue';
import Educacion from './components/EducacionComponente.vue';
import ExperienciaComponente from './components/ExperienciaComponente.vue';
import ProyectosComponente from './components/ProyectosComponente.vue';
import HabilidadesComponente from './components/HabilidadesComponente.vue';
</script>

<template>
 <header>
  <NavBar />
  <DatosPersonales />
 </header>
  <main>
    <section id="educacion"><h2>Educación - Cursos</h2>
    <Educacion />
    </section>
    <section id="experiencia"><h2>Experiencia</h2>
    <ExperienciaComponente />
    </section>
    <section id="proyectos"><h2>Proyectos</h2>
    <ProyectosComponente />
    </section>
    <section id="habilidades"><h2>Habilidades</h2>
    <HabilidadesComponente />
    </section>
  </main>
  <footer>
    <a href="#top">Inicio</a>
    <p>© 2024 Francisco Elías - Portafolio Web</p>
  </footer>
</template>

<style scoped>
footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem;
  font-size: 1.3rem;
}
</style>
