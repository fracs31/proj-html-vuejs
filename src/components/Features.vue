<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Features -->
    <section class="features">
        <!-- Background -->
        <img class="features__bg" src="../assets/img/14.png" alt="Background">
        <!-- Container -->
        <div class="container">
            <!-- Box -->
            <div class="box"> 
                <!-- Titolo -->
                <h2 class="box__title">
                    Popular features that your business needs
                </h2>
                <!-- Descrizione -->
                <div class="box__description">
                    <!-- Testo -->
                    <p class="box__description--text">
                        Faff about only a quid blower I don't want no agro
                        bleeding chimney pot burke tosser cras nice one boot fanny.!
                    </p>
                    <!-- Bottone -->
                    <button class=" box__description--btn btn">
                        Explore More Feature
                    </button>
                </div>
                <!-- Lista -->
                <ul class="list">
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Customized Invoices
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Stock Management
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Receivable & Payables
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Manage Buying
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Powerful & Secure
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Fastest Return Filing
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Monthly Detailed
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Titolo -->
                            <h3 class="card__title">
                                Product Management
                            </h3>
                            <!-- Immagine -->
                            <img class="card__image" src="../assets/img/logo-2.png" alt="">
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Features */
    .features {
        padding-top: 155px;
        position: relative;
    }
    /* Sfondo delle features */
    .features__bg {
        width: 700px;
        position: absolute;
        z-index: -1;
        top: 0px;
        left: 0px;
        transform: translate(-50%, 0%);
    }
    /* Titolo */
    .box__title {
        font-size: 36px;
        font-weight: normal;
    }
    /* Descrizione */
    .box__description {
        margin-bottom: 40px;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }
    /* Testo */
    .box__description--text {
        width: 515px;
        margin-top: 35px;
        color: var(--grey);
    }
    /* Bottone del box */
    .box__description--btn {
        margin-right: 45px;
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
    }
    /* Lista */
    .list {
        display: flex;
        flex-wrap: wrap;
        gap: 30px;
    }
    /* Elemento della lista */
    .list-item {
        flex-basis: calc((100% / 4) - (30px * (3 / 4)));
    }
    /* Carta */
    .card {
        padding: 0px 20px;
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    }
    /* Titolo della carta */
    .card__title {
        font-weight: 500;
        padding: 20px 0px;
    }
    /* Immagine della carta */
    .card__image {
        width: 50px;
        margin-bottom: 40px;
    }
</style>