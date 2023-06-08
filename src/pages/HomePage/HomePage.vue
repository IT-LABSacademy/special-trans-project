<template>
    <div class="home-page">
        <HeroSection />
        <ServicesSection />
        <MainMaterialsSection />
    </div>
</template>

<script>

import HeroSection from './sections/HeroSection.vue'
import MainMaterialsSection from './sections/MainMaterialsSection.vue';
import ServicesSection from './sections/ServicesSection.vue';

export default {
    components: { HeroSection, ServicesSection, MainMaterialsSection }
}
</script>