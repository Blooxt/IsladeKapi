<template>
    <section class="py-20 px-6 bg-gradient-to-b from-[#1a0f0f] to-[#0a0a0a]">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-5xl font-bold mb-4">Conoce a los Personajes</h2>
                <p class="text-xl text-[#f6f4f4]/70">Un elenco memorable te espera en esta aventura</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Kapi -->
                <div
                    class="bg-gradient-to-b from-[#d20202]/10 to-transparent border border-[#d20202]/30 rounded-2xl p-6 text-center group hover:border-[#d20202] transition-all">
                    <div
                        class="w-32 h-32 bg-gradient-to-br from-[#d20202] to-[#a58d00] rounded-full mx-auto mb-4 flex items-center justify-center text-4xl">
                        🐒
                    </div>
                    <h3 class="text-2xl font-bold text-[#d20202] mb-2">Kapi</h3>
                    <p class="text-[#f6f4f4]/70 text-sm mb-4">El Protagonista</p>
                    <p class="text-[#f6f4f4]/80">Un joven mono valiente que busca recuperar la reliquia ancestral de su
                        pueblo.</p>
                </div>

                <!-- Mamá Caco -->
                <div
                    class="bg-gradient-to-b from-[#a58d00]/10 to-transparent border border-[#a58d00]/30 rounded-2xl p-6 text-center group hover:border-[#a58d00] transition-all">
                    <div
                        class="w-32 h-32 bg-gradient-to-br from-[#a58d00] to-[#d20202] rounded-full mx-auto mb-4 flex items-center justify-center text-4xl">
                        🧓
                    </div>
                    <h3 class="text-2xl font-bold text-[#a58d00] mb-2">Mamá Caco</h3>
                    <p class="text-[#f6f4f4]/70 text-sm mb-4">La Guía Sabia</p>
                    <p class="text-[#f6f4f4]/80">Abuelita de Kapi y mentora que conoce los secretos de las tradiciones
                        ancestrales.</p>
                </div>

                <!-- Gutan -->
                <div
                    class="bg-gradient-to-b from-[#001eff]/10 to-transparent border border-[#001eff]/30 rounded-2xl p-6 text-center group hover:border-[#001eff] transition-all">
                    <div
                        class="w-32 h-32 bg-gradient-to-br from-[#001eff] to-[#d20202] rounded-full mx-auto mb-4 flex items-center justify-center text-4xl">
                        🦧
                    </div>
                    <h3 class="text-2xl font-bold text-[#001eff] mb-2">Gutan</h3>
                    <p class="text-[#f6f4f4]/70 text-sm mb-4">El Antagonista</p>
                    <p class="text-[#f6f4f4]/80">Poderoso orangután obsesionado con las reliquias sagradas.</p>
                </div>

                <!-- Kokitos -->
                <div
                    class="bg-gradient-to-b from-[#00a86b]/10 to-transparent border border-[#00a86b]/30 rounded-2xl p-6 text-center group hover:border-[#00a86b] transition-all">
                    <div
                        class="w-32 h-32 bg-gradient-to-br from-[#00a86b] to-[#a58d00] rounded-full mx-auto mb-4 flex items-center justify-center text-4xl">
                        🥥
                    </div>
                    <h3 class="text-2xl font-bold text-[#00a86b] mb-2">Kokitos</h3>
                    <p class="text-[#f6f4f4]/70 text-sm mb-4">Enemigos Básicos</p>
                    <p class="text-[#f6f4f4]/80">Criaturas mitad coco mitad seres vivos que protegen la isla.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
</script>