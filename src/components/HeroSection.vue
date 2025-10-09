<template>
    <section class="pt-32 pb-20 px-6 bg-gradient-to-b from-[#0a0a0a] to-[#1a0f0f]">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Contenido Principal -->
                <div class="lg:col-span-7">
                    <div class="inline-block px-4 py-2 bg-[#a58d00]/20 border border-[#a58d00] rounded-full text-[#a58d00] text-sm font-semibold mb-6">
                        Próximamente - Aventura Épica
                    </div>
                    
                    <h1 class="text-5xl lg:text-7xl font-bold mb-6 leading-tight">
                        La Isla de 
                        <span class="text-[#d20202]">Kapi</span>
                    </h1>
                    
                    <p class="text-xl text-[#f6f4f4]/80 mb-8 max-w-2xl leading-relaxed">
                        Únete a Kapi en su misión para recuperar la reliquia ancestral robada de su aldea. 
                        Explora mundos fantásticos, resuelve acertijos y descubre el misterio detrás 
                        de las siete reliquias sagradas.
                    </p>

                    <div class="flex flex-wrap gap-4 mb-8">
                        <button class="px-8 py-4 bg-[#d20202] text-white rounded-xl hover:bg-[#b80202] transition-all flex items-center gap-3 text-lg font-semibold shadow-lg">
                            <Mail class="w-5 h-5" />
                            Notificarme del Lanzamiento
                        </button>
                        <button class="px-8 py-4 border-2 border-[#001eff] text-[#001eff] rounded-xl hover:bg-[#001eff] hover:text-white transition-all text-lg font-semibold">
                            Ver Tráiler
                        </button>
                    </div>

                    <div class="flex items-center gap-6 text-sm text-[#f6f4f4]/60">
                        <div class="flex items-center gap-2">
                            <Monitor class="w-4 h-4" />
                            Próximamente en PC
                        </div>
                        <div class="flex items-center gap-2">
                            <Users class="w-4 h-4" />
                            Edades 10-18 años
                        </div>
                        <div class="flex items-center gap-2">
                            <Gamepad class="w-4 h-4" />
                            Aventura + Educación
                        </div>
                    </div>
                </div>

                <!-- Imagen/Video del Juego -->
                <div class="lg:col-span-5">
                    <div class="relative">
                        <div class="bg-gradient-to-br from-[#d20202]/10 to-[#001eff]/10 border-2 border-[#d20202]/30 rounded-2xl p-2 aspect-video flex items-center justify-center">
                            <div class="text-center text-[#f6f4f4]/50">
                                <Video class="w-16 h-16 mx-auto mb-4" />
                                <p>Tráiler del juego próximamente</p>
                            </div>
                        </div>
                        <div class="absolute -bottom-4 -right-4 bg-[#a58d00] text-black px-4 py-2 rounded-lg font-bold">
                            Beta Próxima
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Mail, Video, Monitor, Users, Gamepad } from 'lucide-vue-next'
</script>