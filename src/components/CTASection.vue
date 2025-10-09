<template>
  <section class="py-20 px-6 bg-gradient-to-b from-[#0a0a0a] to-[#1a0f0f]">
    <div class="max-w-4xl mx-auto text-center">
      <div class="bg-gradient-to-r from-[#d20202]/10 via-[#a58d00]/10 to-[#001eff]/10 border-2 border-[#d20202]/30 rounded-3xl p-12">
        <h2 class="text-5xl font-bold mb-6 leading-tight">
          Sé el Primero en Jugar la 
          <span class="text-[#d20202]">Beta</span>
        </h2>
        <p class="text-xl text-[#f6f4f4]/70 mb-8">
          Regístrate para recibir notificaciones sobre el lanzamiento de la beta y acceso anticipado.
        </p>
        
        <div class="max-w-md mx-auto mb-6">
          <div class="flex gap-2">
            <input 
              type="email" 
              placeholder="Tu correo electrónico"
              class="flex-1 px-4 py-3 bg-[#000000]/50 border border-[#a58d00]/30 rounded-xl text-white placeholder-[#f6f4f4]/50 focus:outline-none focus:border-[#a58d00]"
            >
            <button class="px-6 py-3 bg-[#d20202] text-white rounded-xl hover:bg-[#b80202] transition-all font-semibold">
              Notificarme
            </button>
          </div>
        </div>

        <div class="flex justify-center gap-8 text-sm text-[#f6f4f4]/50">
          <div class="flex items-center gap-2">
            <Shield class="w-4 h-4" />
            Sin spam, solo actualizaciones importantes
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { Shield } from 'lucide-vue-next'
</script>