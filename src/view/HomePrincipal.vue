<script lang="ts" setup>
import AchievementsSection from '@/components/AchievementsSection.vue';
import CTASection from '@/components/CTASection.vue';
import FeaturesSection from '@/components/FeaturesSection.vue';
import GallerySection from '@/components/GallerySection.vue';
import HeroSection from '@/components/HeroSection.vue';
import Navigation from '@/components/Navigation.vue';
import Footer from '@/components/Footer.vue';
import CharactersSection from '@/components/CharactersSection.vue';
import StorySection from '@/components/StorySection.vue';
import EducationalBenefits from '@/components/EducationalBenefits.vue';
import BetaAccessSection from '@/components/BetaAccessSection.vue';

</script>

<template>
    <div class="min-h-screen bg-[#000000] text-[#f6f4f4]">
        <Navigation/>
        <main>
            <HeroSection/>
            <StorySection/>
            <FeaturesSection/>
            <EducationalBenefits/>
            <GallerySection/>
            <BetaAccessSection/>
            <CharactersSection/>
            <AchievementsSection/>
            <CTASection/>
        </main>
        <Footer/>
    </div>
</template>