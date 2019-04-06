<template>
    <span>
        <home-hero></home-hero>
        <home-details></home-details>
        <GoogleMaps/>
    </span>
</template>

<script>
import HomeHero from '@/components/HomeHero';
import HomeDetails from '@/components/HomeDetails';
import GoogleMaps from '@/components/GoogleMaps';

export default {
    name: 'home',
    components: {
        HomeHero,
        HomeDetails,
        GoogleMaps
    }
};
</script>
