<!-- JavaScript -->
<script>
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
                    <li class="list-item active">
                        Home
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        About us
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        Feature
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        Testimonials
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        Contact US
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
    }
    /* Active */
    .list-item.active {
        color: var(--blue);
        position: relative;
    }
    /* Linea */
    .list-item.active::after {
        content: "";
        display: block;
        width: 100%;
        height: 2px;
        background-color: var(--blue);
        position: absolute;
        left: 0px;
        top: 30px;
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
    /* Carrello */
    .cart {
        position: relative;
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
