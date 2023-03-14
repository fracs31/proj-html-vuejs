<!-- JavaScript -->
<script>

//Esporto
export default {
    //Data
    data() {
        return {
            //Elementi della lista
            listItems: [
                {
                    fullName: "Home", //nome
                    active: true, //classe attiva
                    link: "#hero", //link
                },
                {
                    fullName: "About Us", //nome
                    active: false, //classe attiva
                    link: "#sales", //link
                },
                {
                    fullName: "Feature", //nome
                    active: false, //classe attiva
                    link: "#features", //link
                },
                {
                    fullName: "Testimonials", //nome
                    active: false, //classe attiva
                    link: "#testimonials", //link
                },
                {
                    fullName: "Contact Us", //nome
                    active: false, //classe attiva
                    link: "#contact", //link
                },
            ],
        }
    },
    //Metodi
    methods : {
        //Metodo per cambiare la classe attiva agli elementi della lista
        changeStatus(index) {
            //Tolgo la classe attiva a tutti gli elementi della lista
            for (let i = 0; i < this.listItems.length; i++) {
                this.listItems[i].active = false;
            }
            this.listItems[index].active = true; //assegno la classe attiva all'elemento cliccato
        }
    }
}

</script>

<!-- Template -->
<template>
    <!-- Header -->
    <header class="main-header">
        <!-- Container -->
        <div class="container">
            <!-- Navbar -->
            <nav class="navbar">
                <!-- Logo -->
                <div class="logo">
                    <!-- Immagine -->
                    <img class="logo__img" src="../assets/img/logo-2.png" alt="Logo">
                </div>
                <!-- Lista -->
                <ul class="list">
                    <!-- Elemento della lista -->
                    <li class="list-item" v-for="(item, i) in listItems" v-bind:class="(item.active) ? 'active' : ''" v-on:click="changeStatus(i)">
                        <!-- Ancora -->
                        <a v-bind:href="item.link">{{ item.fullName }}</a>
                    </li>
                </ul>
                <!-- Azioni -->
                <div class="actions">
                    <!-- Ricerca -->
                    <span class="search">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </span>
                    <!-- Carrello -->
                    <span class="cart">
                        <i class="fa-solid fa-cart-shopping"></i>
                    </span>
                </div>
                <!-- Get started -->
                <div class="get-started">
                    <!-- Bottone -->
                    <button class="btn">
                        Get Started
                    </button>
                </div>
            </nav>
        </div>
    </header>
</template>

<!-- CSS -->
<style scoped>
    /* Header */
    .main-header {
        padding: 10px 0px;
        background-color: white;
        position: fixed;
        width: 100vw;
        z-index: 999;
    }
    /* Navbar */
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    /* Immagine */
    .logo__img {
        width: 45px;
    }
    /* Lista */
    .list {
        flex-basis: 65%;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        gap: 30px;
    }
    /* Elemento della lista */
    .list-item {
        color: var(--first-black);
        font-size: 16px;
        cursor: pointer;
        transition: 0.6s;
        position: relative;
    }
    /* Linea dell'elemento della lista */
    .list-item::after {
        content: "";
        display: block;
        width: 0%;
        height: 2px;
        background-color: var(--blue);
        position: absolute;
        left: 0px;
        top: 30px;
        transition: 0.4s;
    }
    /* Active */
    .list-item.active {
        color: var(--blue);
    }
    /* Linea della classe active */
    .list-item.active::after {
        width: 100%;
    }
    /* Hover dell'elemento della lista */
    .list-item:hover {
        color: var(--blue);
    }
    /* Linea dell'elemento della lista quando è in hover */
    .list-item:hover::after {
        width: 100%;
    }
    /* Azioni */
    .actions {
        display: flex;
        gap: 25px;
    }
    /* Bottone */
    .btn {
        color: white;
        background-color: var(--blue);
        border: none;
        border-radius: 4px;
        font-size: 16px;
        padding: 10px 15px;
        cursor: pointer;
        transition: 0.8s;
    }
    /* Bottone in hover */
    .btn:hover {
        background-color: var(--first-black);
    }
    /* Ricerca */
    .search {
        cursor: pointer;
    }
    /* Carrello */
    .cart {
        position: relative;
        cursor: pointer;
    }
    /* Pallino */
    .cart::after {
        content: "0";
        font-size: 12px;
        color: white;
        display: block;
        text-align: center;
        line-height: 20px;
        width: 20px;
        aspect-ratio: 1;
        border-radius: 999px;
        background-color: var(--blue);
        position: absolute;
        top: -5px;
        right: -15px;
        z-index: -1;
    }
</style>
