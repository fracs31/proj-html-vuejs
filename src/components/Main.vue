<!-- JavaScript -->
<script>
import Hero from "./Hero.vue"; //importo l'hero
import Marketing from "./Marketing.vue"; //importo la sezione di marketing
import Sales from "./Sales.vue"; //importo la sezione sales
import Features from "./Features.vue"; //importo la sezione delle features

//Esporto
export default {
    //Componenti
    components: {
        Hero, //hero
        Marketing, //marketing
        Sales, //sales
        Features, //features
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
    </main>
</template>

<!-- CSS -->
<style scoped>
</style>