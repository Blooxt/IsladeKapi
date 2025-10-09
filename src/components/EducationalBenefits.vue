<template>
    <section class="py-20 px-6 bg-gradient-to-b from-[#0a0a0a] to-[#1a0f0f]">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-5xl font-bold mb-4">Diversión con Propósito</h2>
                <p class="text-xl text-[#f6f4f4]/70">Aprende mientras vives una aventura épica</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <!-- Beneficios -->
                <div class="space-y-6">
                    <div class="flex gap-4 items-start">
                        <div
                            class="w-12 h-12 bg-[#d20202]/20 rounded-xl flex items-center justify-center flex-shrink-0">
                            <Lightbulb class="w-6 h-6 text-[#d20202]" />
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#f6f4f4] mb-2">Pensamiento Crítico</h3>
                            <p class="text-[#f6f4f4]/80">
                                Resuelve acertijos de cultura general que desafían tu conocimiento
                                y te ayudan a progresar en la historia.
                            </p>
                        </div>
                    </div>

                    <div class="flex gap-4 items-start">
                        <div
                            class="w-12 h-12 bg-[#a58d00]/20 rounded-xl flex items-center justify-center flex-shrink-0">
                            <Target class="w-6 h-6 text-[#a58d00]" />
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#f6f4f4] mb-2">Toma de Decisiones</h3>
                            <p class="text-[#f6f4f4]/80">
                                Evalúa probabilidades y consecuencias en situaciones estratégicas
                                dentro del casino y otros desafíos.
                            </p>
                        </div>
                    </div>

                    <div class="flex gap-4 items-start">
                        <div
                            class="w-12 h-12 bg-[#001eff]/20 rounded-xl flex items-center justify-center flex-shrink-0">
                            <Compass class="w-6 h-6 text-[#001eff]" />
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#f6f4f4] mb-2">Exploración y Curiosidad</h3>
                            <p class="text-[#f6f4f4]/80">
                                Fomenta la curiosidad natural al descubrir secretos y aprender
                                sobre diferentes culturas y conocimientos.
                            </p>
                        </div>
                    </div>

                    <div class="flex gap-4 items-start">
                        <div
                            class="w-12 h-12 bg-[#00a86b]/20 rounded-xl flex items-center justify-center flex-shrink-0">
                            <Puzzle class="w-6 h-6 text-[#00a86b]" />
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#f6f4f4] mb-2">Resolución de Problemas</h3>
                            <p class="text-[#f6f4f4]/80">
                                Desarrolla habilidades para enfrentar y superar obstáculos
                                mediante el razonamiento lógico y la creatividad.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Estadísticas -->
                <div
                    class="bg-gradient-to-br from-[#d20202]/10 to-[#001eff]/10 border-2 border-[#d20202]/30 rounded-2xl p-8">
                    <h3 class="text-2xl font-bold text-center mb-8">Desarrollado para Jóvenes</h3>

                    <div class="space-y-6">
                        <div>
                            <div class="flex justify-between text-sm text-[#f6f4f4]/70 mb-2">
                                <span>Rango de Edad Ideal</span>
                                <span>10-18 años</span>
                            </div>
                            <div class="w-full bg-[#f6f4f4]/20 rounded-full h-2">
                                <div class="bg-gradient-to-r from-[#d20202] to-[#001eff] h-2 rounded-full w-3/4"></div>
                            </div>
                        </div>

                        <div>
                            <div class="flex justify-between text-sm text-[#f6f4f4]/70 mb-2">
                                <span>Contenido Educativo</span>
                                <span>85%</span>
                            </div>
                            <div class="w-full bg-[#f6f4f4]/20 rounded-full h-2">
                                <div class="bg-gradient-to-r from-[#a58d00] to-[#00a86b] h-2 rounded-full w-4/5"></div>
                            </div>
                        </div>

                        <div>
                            <div class="flex justify-between text-sm text-[#f6f4f4]/70 mb-2">
                                <span>Duración Estimada</span>
                                <span>5-7 horas</span>
                            </div>
                            <div class="w-full bg-[#f6f4f4]/20 rounded-full h-2">
                                <div class="bg-gradient-to-r from-[#001eff] to-[#d20202] h-2 rounded-full w-2/3"></div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-8 p-4 bg-black/30 rounded-xl">
                        <p class="text-sm text-[#f6f4f4]/80 text-center">
                            "Un juego que equilibra perfectamente entretenimiento y aprendizaje,
                            ideal para el desarrollo cognitivo de jóvenes jugadores."
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Lightbulb, Target, Compass, Puzzle } from 'lucide-vue-next'
</script>