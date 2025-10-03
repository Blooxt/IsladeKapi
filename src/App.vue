<script setup lang="ts">
import { Compass, Scroll, Sword, Sparkles, Users, Trophy, Download, Play } from 'lucide-vue-next'
</script>

<template>
  <div class="min-h-screen bg-[#000000] text-[#f6f4f4]">
    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 bg-[#000000]/80 backdrop-blur-md border-b border-[#d20202]/20">
      <div class="max-w-7xl mx-auto px-6 py-4">
        <div class="flex items-center justify-between">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 bg-gradient-to-br from-[#d20202] to-[#a58d00] rounded-lg flex items-center justify-center">
              <Compass class="w-6 h-6 text-[#f6f4f4]" />
            </div>
            <span class="text-2xl font-bold">Isla de Kapi</span>
          </div>
          <div class="flex items-center gap-4">
            <button class="px-6 py-2 border border-[#a58d00] text-[#a58d00] rounded-lg hover:bg-[#a58d00] hover:text-[#000000] transition-all">
              Trailer
            </button>
            <button class="px-6 py-2 bg-[#d20202] text-[#f6f4f4] rounded-lg hover:bg-[#d20202]/80 transition-all flex items-center gap-2">
              <Play class="w-4 h-4" />
              Jugar Ahora
            </button>
          </div>
        </div>
      </div>
    </nav>

    <!-- Hero Section - Bento Style -->
    <section class="pt-32 pb-20 px-6">
      <div class="max-w-7xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
          <!-- Main Hero Card -->
          <div class="lg:col-span-8 bg-gradient-to-br from-[#d20202]/10 to-[#001eff]/10 border border-[#d20202]/30 rounded-3xl p-12 relative overflow-hidden">
            <div class="absolute top-0 right-0 w-64 h-64 bg-[#d20202]/20 rounded-full blur-3xl"></div>
            <div class="absolute bottom-0 left-0 w-64 h-64 bg-[#001eff]/20 rounded-full blur-3xl"></div>
            <div class="relative z-10">
              <div class="inline-block px-4 py-2 bg-[#a58d00]/20 border border-[#a58d00] rounded-full text-[#a58d00] text-sm font-semibold mb-6">
                Aventura Épica 2024
              </div>
              <h1 class="text-6xl lg:text-7xl font-bold mb-6 leading-tight">
                Descubre los<br/>
                <span class="text-[#d20202]">Secretos</span> de la<br/>
                <span class="text-[#a58d00]">Isla de Kapi</span>
              </h1>
              <p class="text-xl text-[#f6f4f4]/70 mb-8 max-w-2xl leading-relaxed">
                Embárcate en una aventura inolvidable donde cada decisión cuenta y cada rincón esconde un misterio por resolver.
              </p>
              <div class="flex flex-wrap gap-4">
                <button class="px-8 py-4 bg-[#d20202] text-[#f6f4f4] rounded-xl hover:bg-[#d20202]/80 transition-all flex items-center gap-3 text-lg font-semibold">
                  <Download class="w-5 h-5" />
                  Descargar Gratis
                </button>
                <button class="px-8 py-4 border-2 border-[#001eff] text-[#001eff] rounded-xl hover:bg-[#001eff] hover:text-[#f6f4f4] transition-all text-lg font-semibold">
                  Ver Gameplay
                </button>
              </div>
            </div>
          </div>

          <!-- Stats Cards -->
          <div class="lg:col-span-4 flex flex-col gap-6">
            <div class="bg-[#d20202]/10 border border-[#d20202] rounded-2xl p-6 hover:bg-[#d20202]/20 transition-all">
              <div class="text-4xl font-bold text-[#d20202] mb-2">500K+</div>
              <div class="text-[#f6f4f4]/70">Jugadores Activos</div>
            </div>
            <div class="bg-[#a58d00]/10 border border-[#a58d00] rounded-2xl p-6 hover:bg-[#a58d00]/20 transition-all">
              <div class="text-4xl font-bold text-[#a58d00] mb-2">4.9★</div>
              <div class="text-[#f6f4f4]/70">Calificación</div>
            </div>
            <div class="bg-[#001eff]/10 border border-[#001eff] rounded-2xl p-6 hover:bg-[#001eff]/20 transition-all">
              <div class="text-4xl font-bold text-[#001eff] mb-2">50+</div>
              <div class="text-[#f6f4f4]/70">Horas de Juego</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Features Bento Grid -->
    <section class="py-20 px-6">
      <div class="max-w-7xl mx-auto">
        <div class="text-center mb-16">
          <h2 class="text-5xl font-bold mb-4">Características Épicas</h2>
          <p class="text-xl text-[#f6f4f4]/70">Todo lo que necesitas para una aventura inolvidable</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <!-- Feature 1 - Large -->
          <div class="md:col-span-2 bg-gradient-to-br from-[#d20202]/5 to-transparent border border-[#d20202]/30 rounded-3xl p-8 hover:border-[#d20202] transition-all group">
            <div class="w-16 h-16 bg-[#d20202]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#d20202] transition-all">
              <Compass class="w-8 h-8 text-[#d20202] group-hover:text-[#f6f4f4]" />
            </div>
            <h3 class="text-3xl font-bold mb-4 text-[#d20202]">Mundo Abierto Masivo</h3>
            <p class="text-lg text-[#f6f4f4]/70 leading-relaxed">
              Explora una isla vasta llena de biomas únicos, desde selvas tropicales hasta volcanes activos. Cada zona tiene sus propios secretos y desafíos.
            </p>
          </div>

          <!-- Feature 2 -->
          <div class="bg-gradient-to-br from-[#a58d00]/5 to-transparent border border-[#a58d00]/30 rounded-3xl p-8 hover:border-[#a58d00] transition-all group">
            <div class="w-16 h-16 bg-[#a58d00]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#a58d00] transition-all">
              <Scroll class="w-8 h-8 text-[#a58d00] group-hover:text-[#000000]" />
            </div>
            <h3 class="text-2xl font-bold mb-4 text-[#a58d00]">Historia Profunda</h3>
            <p class="text-[#f6f4f4]/70">
              Descubre la mitología ancestral de Kapi a través de misiones épicas.
            </p>
          </div>

          <!-- Feature 3 -->
          <div class="bg-gradient-to-br from-[#001eff]/5 to-transparent border border-[#001eff]/30 rounded-3xl p-8 hover:border-[#001eff] transition-all group">
            <div class="w-16 h-16 bg-[#001eff]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#001eff] transition-all">
              <Sword class="w-8 h-8 text-[#001eff] group-hover:text-[#f6f4f4]" />
            </div>
            <h3 class="text-2xl font-bold mb-4 text-[#001eff]">Combate Dinámico</h3>
            <p class="text-[#f6f4f4]/70">
              Sistema de combate fluido con combos y habilidades especiales.
            </p>
          </div>

          <!-- Feature 4 -->
          <div class="bg-gradient-to-br from-[#d20202]/5 to-transparent border border-[#d20202]/30 rounded-3xl p-8 hover:border-[#d20202] transition-all group">
            <div class="w-16 h-16 bg-[#d20202]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#d20202] transition-all">
              <Sparkles class="w-8 h-8 text-[#d20202] group-hover:text-[#f6f4f4]" />
            </div>
            <h3 class="text-2xl font-bold mb-4 text-[#d20202]">Magia Ancestral</h3>
            <p class="text-[#f6f4f4]/70">
              Domina poderes elementales y hechizos únicos de la isla.
            </p>
          </div>

          <!-- Feature 5 - Large -->
          <div class="md:col-span-2 bg-gradient-to-br from-[#a58d00]/5 to-transparent border border-[#a58d00]/30 rounded-3xl p-8 hover:border-[#a58d00] transition-all group">
            <div class="w-16 h-16 bg-[#a58d00]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#a58d00] transition-all">
              <Users class="w-8 h-8 text-[#a58d00] group-hover:text-[#000000]" />
            </div>
            <h3 class="text-3xl font-bold mb-4 text-[#a58d00]">Modo Multijugador</h3>
            <p class="text-lg text-[#f6f4f4]/70 leading-relaxed">
              Únete con amigos en misiones cooperativas o compite en arenas PvP. La aventura es mejor cuando se comparte.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Gallery Showcase -->
    <section class="py-20 px-6 bg-gradient-to-b from-transparent via-[#d20202]/5 to-transparent">
      <div class="max-w-7xl mx-auto">
        <div class="text-center mb-16">
          <h2 class="text-5xl font-bold mb-4">Explora la Isla</h2>
          <p class="text-xl text-[#f6f4f4]/70">Cada rincón es una nueva aventura</p>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-4">
          <div class="col-span-2 row-span-2 relative group overflow-hidden rounded-3xl border-2 border-[#d20202]/30 hover:border-[#d20202] transition-all">
            <img src="" alt="Selva" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-[#000000] via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-all">
              <div class="absolute bottom-6 left-6">
                <h3 class="text-2xl font-bold text-[#f6f4f4] mb-2">La Selva Perdida</h3>
                <p class="text-[#f6f4f4]/70">Explora la densa vegetación</p>
              </div>
            </div>
          </div>

          <div class="relative group overflow-hidden rounded-2xl border-2 border-[#a58d00]/30 hover:border-[#a58d00] transition-all">
            <img src="" alt="Volcán" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-[#000000] via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-all">
              <div class="absolute bottom-4 left-4">
                <h3 class="text-lg font-bold text-[#f6f4f4]">Volcán Kapi</h3>
              </div>
            </div>
          </div>

          <div class="relative group overflow-hidden rounded-2xl border-2 border-[#001eff]/30 hover:border-[#001eff] transition-all">
            <img src="" alt="Templo" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-[#000000] via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-all">
              <div class="absolute bottom-4 left-4">
                <h3 class="text-lg font-bold text-[#f6f4f4]">Templo Antiguo</h3>
              </div>
            </div>
          </div>

          <div class="relative group overflow-hidden rounded-2xl border-2 border-[#d20202]/30 hover:border-[#d20202] transition-all">
            <img src="" alt="Cuevas" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-[#000000] via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-all">
              <div class="absolute bottom-4 left-4">
                <h3 class="text-lg font-bold text-[#f6f4f4]">Cuevas Cristal</h3>
              </div>
            </div>
          </div>

          <div class="relative group overflow-hidden rounded-2xl border-2 border-[#a58d00]/30 hover:border-[#a58d00] transition-all">
            <img src="" alt="Playa" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-[#000000] via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-all">
              <div class="absolute bottom-4 left-4">
                <h3 class="text-lg font-bold text-[#f6f4f4]">Bahía Dorada</h3>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Achievements -->
    <section class="py-20 px-6">
      <div class="max-w-7xl mx-auto">
        <div class="bg-gradient-to-r from-[#d20202]/10 via-[#a58d00]/10 to-[#001eff]/10 border-2 border-[#d20202]/30 rounded-3xl p-12">
          <div class="text-center mb-12">
            <Trophy class="w-16 h-16 text-[#a58d00] mx-auto mb-4" />
            <h2 class="text-4xl font-bold mb-4">Logros y Recompensas</h2>
            <p class="text-xl text-[#f6f4f4]/70">Completa desafíos y desbloquea contenido exclusivo</p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="text-center">
              <div class="w-20 h-20 bg-[#d20202]/20 border-2 border-[#d20202] rounded-full flex items-center justify-center mx-auto mb-4">
                <span class="text-3xl font-bold text-[#d20202]">100+</span>
              </div>
              <h3 class="text-xl font-bold mb-2">Logros Únicos</h3>
              <p class="text-[#f6f4f4]/70">Desafíos para todos los estilos</p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-[#a58d00]/20 border-2 border-[#a58d00] rounded-full flex items-center justify-center mx-auto mb-4">
                <span class="text-3xl font-bold text-[#a58d00]">50+</span>
              </div>
              <h3 class="text-xl font-bold mb-2">Objetos Legendarios</h3>
              <p class="text-[#f6f4f4]/70">Equipo épico por descubrir</p>
            </div>

            <div class="text-center">
              <div class="w-20 h-20 bg-[#001eff]/20 border-2 border-[#001eff] rounded-full flex items-center justify-center mx-auto mb-4">
                <span class="text-3xl font-bold text-[#001eff]">20+</span>
              </div>
              <h3 class="text-xl font-bold mb-2">Jefes Épicos</h3>
              <p class="text-[#f6f4f4]/70">Batallas memorables</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Final CTA -->
    <section class="py-32 px-6">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-6xl font-bold mb-6 leading-tight">
          Tu Aventura<br/>
          <span class="text-[#d20202]">Comienza Ahora</span>
        </h2>
        <p class="text-2xl text-[#f6f4f4]/70 mb-12">
          Descarga gratis y sumérgete en el mundo de Isla de Kapi
        </p>
        <div class="flex flex-wrap justify-center gap-6">
          <button class="px-12 py-5 bg-[#d20202] text-[#f6f4f4] rounded-2xl hover:bg-[#d20202]/80 transition-all text-xl font-bold flex items-center gap-3">
            <Download class="w-6 h-6" />
            Descargar para PC
          </button>
          <button class="px-12 py-5 bg-[#a58d00] text-[#000000] rounded-2xl hover:bg-[#a58d00]/80 transition-all text-xl font-bold flex items-center gap-3">
            <Download class="w-6 h-6" />
            Descargar para Consola
          </button>
        </div>
        <p class="text-[#f6f4f4]/50 mt-8">Disponible en PC, PlayStation, Xbox y Nintendo Switch</p>
      </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-[#d20202]/20 py-12 px-6">
      <div class="max-w-7xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
          <div>
            <div class="flex items-center gap-3 mb-4">
              <div class="w-10 h-10 bg-gradient-to-br from-[#d20202] to-[#a58d00] rounded-lg flex items-center justify-center">
                <Compass class="w-6 h-6 text-[#f6f4f4]" />
              </div>
              <span class="text-xl font-bold">Isla de Kapi</span>
            </div>
            <p class="text-[#f6f4f4]/70">La aventura épica que estabas esperando.</p>
          </div>

          <div>
            <h4 class="font-bold mb-4 text-[#d20202]">Juego</h4>
            <ul class="space-y-2 text-[#f6f4f4]/70">
              <li><a href="#" class="hover:text-[#d20202] transition-colors">Características</a></li>
              <li><a href="#" class="hover:text-[#d20202] transition-colors">Historia</a></li>
              <li><a href="#" class="hover:text-[#d20202] transition-colors">Personajes</a></li>
            </ul>
          </div>

          <div>
            <h4 class="font-bold mb-4 text-[#a58d00]">Comunidad</h4>
            <ul class="space-y-2 text-[#f6f4f4]/70">
              <li><a href="#" class="hover:text-[#a58d00] transition-colors">Discord</a></li>
              <li><a href="#" class="hover:text-[#a58d00] transition-colors">Foros</a></li>
              <li><a href="#" class="hover:text-[#a58d00] transition-colors">Guías</a></li>
            </ul>
          </div>

          <div>
            <h4 class="font-bold mb-4 text-[#001eff]">Soporte</h4>
            <ul class="space-y-2 text-[#f6f4f4]/70">
              <li><a href="#" class="hover:text-[#001eff] transition-colors">FAQ</a></li>
              <li><a href="#" class="hover:text-[#001eff] transition-colors">Contacto</a></li>
              <li><a href="#" class="hover:text-[#001eff] transition-colors">Reportar Bug</a></li>
            </ul>
          </div>
        </div>

        <div class="border-t border-[#f6f4f4]/10 pt-8 text-center text-[#f6f4f4]/50">
          <p>© 2025 Isla de Kapi. Todos los derechos reservados.</p>
        </div>
      </div>
    </footer>
  </div>
</template>