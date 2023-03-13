<!-- JavaScript -->
<script>
import Hero from "./Hero.vue"; //importo l'hero
import Marketing from "./Marketing.vue"; //importo la sezione di marketing

//Esporto
export default {
    //Componenti
    components: {
        Hero, //hero
        Marketing, //marketing
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
    </main>
</template>

<!-- CSS -->
<style scoped>
</style>