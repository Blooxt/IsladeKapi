<template>
    <section class="py-20 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-5xl font-bold mb-4">Características Épicas</h2>
                <p class="text-xl text-[#f6f4f4]/70">Todo lo que necesitas para una aventura inolvidable</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Feature 1 - Large -->
                <div
                    class="md:col-span-2 bg-gradient-to-br from-[#d20202]/5 to-transparent border border-[#d20202]/30 rounded-3xl p-8 hover:border-[#d20202] transition-all group">
                    <div
                        class="w-16 h-16 bg-[#d20202]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#d20202] transition-all">
                        <Compass class="w-8 h-8 text-[#d20202] group-hover:text-[#f6f4f4]" />
                    </div>
                    <h3 class="text-3xl font-bold mb-4 text-[#d20202]">Mundo de aventura</h3>
                    <p class="text-lg text-[#f6f4f4]/70 leading-relaxed">
                        Explora la isla de kapi con lugares fantasticos como selvas, cuevas e incluso casinos, cada uno
                        con secretos y desafíos únicos.
                    </p>
                </div>

                <!-- Feature 2 -->
                <div
                    class="bg-gradient-to-br from-[#a58d00]/5 to-transparent border border-[#a58d00]/30 rounded-3xl p-8 hover:border-[#a58d00] transition-all group">
                    <div
                        class="w-16 h-16 bg-[#a58d00]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#a58d00] transition-all">
                        <Scroll class="w-8 h-8 text-[#a58d00] group-hover:text-[#000000]" />
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-[#a58d00]">Historia Profunda</h3>
                    <p class="text-[#f6f4f4]/70">
                        Este videojuego narra la aventura de Kapi, un mono que, tras la destrucción de su aldea y el
                        robo de una reliquia ancestral, se embarca en una misión para recuperarla.
                    </p>
                </div>

                <!-- Feature 3 -->
                <div
                    class="bg-gradient-to-br from-[#001eff]/5 to-transparent border border-[#001eff]/30 rounded-3xl p-8 hover:border-[#001eff] transition-all group">
                    <div
                        class="w-16 h-16 bg-[#001eff]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#001eff] transition-all">
                        <Sword class="w-8 h-8 text-[#001eff] group-hover:text-[#f6f4f4]" />
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-[#001eff]">Combate</h3>
                    <p class="text-[#f6f4f4]/70">
                        Enfréntate a rivales y obstáculos que pondrán a prueba tu habilidad.
                    </p>
                </div>

                <!-- Feature 4 -->
                <div
                    class="bg-gradient-to-br from-[#d20202]/5 to-transparent border border-[#d20202]/30 rounded-3xl p-8 hover:border-[#d20202] transition-all group">
                    <div
                        class="w-16 h-16 bg-[#d20202]/20 rounded-2xl flex items-center justify-center mb-6 group-hover:bg-[#d20202] transition-all">
                        <Sparkles class="w-8 h-8 text-[#d20202] group-hover:text-[#f6f4f4]" />
                    </div>
                    <h3 class="text-2xl font-bold mb-4 text-[#d20202]">La reliquia</h3>
                    <p class="text-[#f6f4f4]/70">
                        Recupera la reliquia y descubre el origen del villano que amenaza la isla.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Compass, Scroll, Sword, Sparkles } from 'lucide-vue-next'
</script>