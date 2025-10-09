<script lang="ts" setup>
import AchievementsSection from '@/components/AchievementsSection.vue';
import CTASection from '@/components/CTASection.vue';
import FeaturesSection from '@/components/FeaturesSection.vue';
import GallerySection from '@/components/GallerySection.vue';
import HeroSection from '@/components/HeroSection.vue';
import Navigation from '@/components/Navigation.vue';
import Footer from '@/components/Footer.vue';

</script>

<template>
    <div class="min-h-screen bg-[#000000] text-[#f6f4f4]">
        <Navigation/>
        <HeroSection/>
        <FeaturesSection/>
        <GallerySection/>
        <AchievementsSection/>
        <CTASection/>
        <Footer/>
    </div>
</template>