<template>
    <nav class="fixed top-0 w-full z-50 bg-[#000000]/80 backdrop-blur-md border-b border-[#d20202]/20">
        <div class="max-w-7xl mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center gap-3">
                    <div
                        class="w-10 h-10 bg-gradient-to-br from-[#d20202] to-[#a58d00] rounded-lg flex items-center justify-center">
                        <Compass class="w-6 h-6 text-[#f6f4f4]" />
                    </div>
                    <span class="text-2xl font-bold">La Isla de Kapi</span>
                </div>
                <div class="flex items-center gap-4">
                    <button
                        class="px-6 py-2 border border-[#a58d00] text-[#a58d00] rounded-lg hover:bg-[#a58d00] hover:text-[#000000] transition-all">
                        Trailer
                    </button>
                    <button
                        class="px-6 py-2 bg-[#d20202] text-[#f6f4f4] rounded-lg hover:bg-[#d20202]/80 transition-all flex items-center gap-2">
                        <Play class="w-4 h-4" />
                        Jugar Ahora
                    </button>
                </div>
            </div>
        </div>
    </nav>
</template>

<script setup lang="ts">
import { Compass, Play } from 'lucide-vue-next'
</script>