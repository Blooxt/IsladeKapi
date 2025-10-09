<template>
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
      </div>
      <p class="text-[#f6f4f4]/50 mt-8">Disponible en PC, PlayStation, Xbox y Nintendo Switch</p>
    </div>
  </section>
</template>

<script setup lang="ts">
import { Download } from 'lucide-vue-next'
</script>