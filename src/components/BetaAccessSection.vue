<template>
    <section class="py-20 px-6 bg-gradient-to-b from-[#1a0f0f] to-[#0a0a0a]">
        <div class="max-w-6xl mx-auto">
            <div class="bg-gradient-to-r from-[#d20202]/10 via-[#a58d00]/10 to-[#001eff]/10 border-2 border-[#d20202]/30 rounded-3xl p-12 text-center">
                <div class="w-20 h-20 bg-[#d20202] rounded-2xl flex items-center justify-center mx-auto mb-6">
                    <Crown class="w-10 h-10 text-white" />
                </div>
                
                <h2 class="text-4xl font-bold mb-4">Acceso Anticipado a la Beta</h2>
                <p class="text-xl text-[#f6f4f4]/70 mb-8 max-w-2xl mx-auto">
                    Sé de los primeros en explorar la Isla de Kapi. Regístrate para tener oportunidad 
                    de participar en la beta cerrada de PC.
                </p>

                <div class="max-w-md mx-auto mb-8">
                    <div class="flex flex-col sm:flex-row gap-4">
                        <input 
                            type="email" 
                            placeholder="tu.email@ejemplo.com"
                            class="flex-1 px-4 py-3 bg-black/50 border border-[#a58d00]/30 rounded-xl text-white placeholder-[#f6f4f4]/50 focus:outline-none focus:border-[#a58d00]"
                        >
                        <button class="px-8 py-3 bg-[#d20202] text-white rounded-xl hover:bg-[#b80202] transition-all font-semibold whitespace-nowrap">
                            Solicitar Acceso
                        </button>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-2xl mx-auto">
                    <div class="text-center">
                        <div class="w-12 h-12 bg-[#d20202]/20 rounded-xl flex items-center justify-center mx-auto mb-3">
                            <Calendar class="w-6 h-6 text-[#d20202]" />
                        </div>
                        <h4 class="font-bold text-[#d20202] mb-2">Beta Próxima</h4>
                        <p class="text-sm text-[#f6f4f4]/70">Primer trimestre 2024</p>
                    </div>

                    <div class="text-center">
                        <div class="w-12 h-12 bg-[#a58d00]/20 rounded-xl flex items-center justify-center mx-auto mb-3">
                            <Users class="w-6 h-6 text-[#a58d00]" />
                        </div>
                        <h4 class="font-bold text-[#a58d00] mb-2">Cupos Limitados</h4>
                        <p class="text-sm text-[#f6f4f4]/70">Primeros 1000 registrados</p>
                    </div>

                    <div class="text-center">
                        <div class="w-12 h-12 bg-[#001eff]/20 rounded-xl flex items-center justify-center mx-auto mb-3">
                            <MessageCircle class="w-6 h-6 text-[#001eff]" />
                        </div>
                        <h4 class="font-bold text-[#001eff] mb-2">Feedback Valorado</h4>
                        <p class="text-sm text-[#f6f4f4]/70">Ayuda a mejorar el juego</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Crown, Calendar, Users, MessageCircle } from 'lucide-vue-next'
</script>