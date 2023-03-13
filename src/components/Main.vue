<!-- JavaScript -->
<script>
import Hero from "./Hero.vue"; //importo l'hero
import Marketing from "./Marketing.vue"; //importo la sezione di marketing
import Sales from "./Sales.vue"; //importo la sezione sales
import Features from "./Features.vue"; //importo la sezione delle features
import Testimonials from "./Testimonials.vue"; //importo la sezione delle testimonials

//Esporto
export default {
    //Componenti
    components: {
        Hero, //hero
        Marketing, //marketing
        Sales, //sales
        Features, //features
        Testimonials, //testimonials
    }
}
</script>

<!-- Template -->
<template>
    <!-- Main -->
    <main class="main-content">
        <!-- Hero -->
        <Hero></Hero>
        <!-- Marketing -->
        <Marketing></Marketing>
        <!-- Sales -->
        <Sales></Sales>
        <!-- Features -->
        <Features></Features>
        <!-- Testimonials -->
        <Testimonials></Testimonials>
    </main>
</template>

<!-- CSS -->
<style scoped>
</style>