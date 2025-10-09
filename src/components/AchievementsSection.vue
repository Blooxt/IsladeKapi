<template>
    <section class="py-20 px-6">
        <div class="max-w-7xl mx-auto">
            <div
                class="bg-gradient-to-r from-[#d20202]/10 via-[#a58d00]/10 to-[#001eff]/10 border-2 border-[#d20202]/30 rounded-3xl p-12">
                <div class="text-center mb-12">
                    <Trophy class="w-16 h-16 text-[#a58d00] mx-auto mb-4" />
                    <h2 class="text-4xl font-bold mb-4">Logros y Recompensas</h2>
                    <p class="text-xl text-[#f6f4f4]/70">Completa desafíos y desbloquea contenido exclusivo</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="text-center">
                        <div
                            class="w-20 h-20 bg-[#d20202]/20 border-2 border-[#d20202] rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl font-bold text-[#d20202]">🍌</span>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Coleccionables</h3>
                        <p class="text-[#f6f4f4]/70">Colecciona las bananas esparcidas por el mundo</p>
                    </div>

                    <div class="text-center">
                        <div
                            class="w-20 h-20 bg-[#a58d00]/20 border-2 border-[#a58d00] rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl font-bold text-[#a58d00]">🐒</span>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Personajes memorables</h3>
                        <p class="text-[#f6f4f4]/70">Un cast de monos apostadores</p>
                    </div>

                    <div class="text-center">
                        <div
                            class="w-20 h-20 bg-[#001eff]/20 border-2 border-[#001eff] rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl font-bold text-[#001eff]">🎲</span>
                        </div>
                        <h3 class="text-xl font-bold mb-2">Jefes Épicos</h3>
                        <p class="text-[#f6f4f4]/70">Batallas memorables</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Trophy } from 'lucide-vue-next'
</script>