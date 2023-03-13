<!-- JavaScript -->
<script>
import Header from "./components/Header.vue"; //importo l'header
import Main from "./components/Main.vue"; //importo il main
import Footer from "./components/Footer.vue"; //importo il footer

//Esporto
export default {
    //Componenti
    components: {
        Header, //header
        Main, //main
        Footer, //footer
    }
}
</script>

<!-- Template -->
<template>
    <!-- Header -->
    <Header></Header>
    <!-- Main -->
    <Main></Main>
    <!-- Footer -->
    <Footer></Footer>
</template>

<!-- CSS -->
<style scoped>
</style>
