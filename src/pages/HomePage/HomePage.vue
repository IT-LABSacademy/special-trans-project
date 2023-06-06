<template>
    <div class="home-page">
        <HeroSection />
        <ServicesSection />
    </div>
</template>

<script>

import HeroSection from './sections/HeroSection.vue'
import ServicesSection from './sections/ServicesSection.vue';

export default {
    components: { HeroSection, ServicesSection }
}
</script>