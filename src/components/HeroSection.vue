<template>
    <section class="pt-32 pb-20 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- Main Hero Card -->
                <div
                    class="lg:col-span-8 bg-gradient-to-br from-[#d20202]/10 to-[#001eff]/10 border border-[#d20202]/30 rounded-3xl p-12 relative overflow-hidden">
                    <div class="absolute top-0 right-0 w-64 h-64 bg-[#d20202]/20 rounded-full blur-3xl"></div>
                    <div class="absolute bottom-0 left-0 w-64 h-64 bg-[#001eff]/20 rounded-full blur-3xl"></div>
                    <div class="relative z-10">
                        <div
                            class="inline-block px-4 py-2 bg-[#a58d00]/20 border border-[#a58d00] rounded-full text-[#a58d00] text-sm font-semibold mb-6">
                            Ponte a hacer monadas como Kapi!
                        </div>
                        <h1 class="text-6xl lg:text-7xl font-bold mb-6 leading-tight">
                            Descubre los<br />
                            <span class="text-[#d20202]">Secretos</span> de la<br />
                            <span class="text-[#a58d00]">Isla de Kapi</span>
                        </h1>
                        <p class="text-xl text-[#f6f4f4]/70 mb-8 max-w-2xl leading-relaxed">
                            Acompaña a Kapi en su misión por recuperar la reliquia sagrada de su aldea, enfrentando
                            desafíos, enemigos y misterios ancestrales.
                        </p>
                        <div class="flex flex-wrap gap-4">
                            <button
                                class="px-8 py-4 bg-[#d20202] text-[#f6f4f4] rounded-xl hover:bg-[#d20202]/80 transition-all flex items-center gap-3 text-lg font-semibold">
                                <Download class="w-5 h-5" />
                                Proximamente Beta en PC
                            </button>
                            <button
                                class="px-8 py-4 border-2 border-[#001eff] text-[#001eff] rounded-xl hover:bg-[#001eff] hover:text-[#f6f4f4] transition-all text-lg font-semibold">
                                Ver Gameplay
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Stats Cards -->
                <div class="lg:col-span-4 flex flex-col gap-6">
                    <div
                        class="bg-[#d20202]/10 border border-[#d20202] rounded-2xl p-6 hover:bg-[#d20202]/20 transition-all">
                        <div class="text-4xl font-bold text-[#d20202] mb-2">En desarrollo</div>
                        <div class="text-[#f6f4f4]/70">Beta próximamente</div>
                    </div>
                    <div
                        class="bg-[#a58d00]/10 border border-[#a58d00] rounded-2xl p-6 hover:bg-[#a58d00]/20 transition-all">
                        <div class="text-4xl font-bold text-[#a58d00] mb-2">Juegos de casino</div>
                        <div class="text-[#f6f4f4]/70">Con un giro de chimpances</div>
                    </div>
                    <div
                        class="bg-[#001eff]/10 border border-[#001eff] rounded-2xl p-6 hover:bg-[#001eff]/20 transition-all">
                        <div class="text-4xl font-bold text-[#001eff] mb-2">5+</div>
                        <div class="text-[#f6f4f4]/70">Horas de Juego</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Download } from 'lucide-vue-next'
</script>