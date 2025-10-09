<template>
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
</template>

<script setup lang="ts">
import { Compass } from 'lucide-vue-next'
</script>