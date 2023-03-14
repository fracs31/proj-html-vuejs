<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Testimonials -->
    <section class="testimonials" id="testimonials">
        <!-- Sfondo -->
        <img class="testimonials__bg" src="../assets/img/15.png" alt="Background">
        <!-- Box -->
        <div class="box">
            <!-- Container -->
            <div class="container">
                <!-- Titolo -->
                <h2 class="box__title">
                    Our Testimonials
                </h2>
                <!-- Testo -->
                <p class="box__text">
                    If you are planning on devoloping a product landing app or website,
                    take a look at this beautiful-crafted
                </p>
            </div>
            <!-- Container -->
            <div class="container">
                <!-- Persone -->
                <div class="people">
                    <!-- Lista -->
                    <ul class="list">
                        <!-- Elemento della lista -->
                        <li class="list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Sfondo della carta -->
                                <img class="card__bg" src="../assets/img/quote.png" alt="Background">
                                <!-- Immagine della carta -->
                                <div class="card__image">
                                    <!-- Immagine -->
                                    <img class="card__image--img" src="../assets/img/26.jpeg" alt="Julia Aann">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Julia Aann <span class="card__title--title__little">- COO Sofbox</span>
                                    </h3>
                                </div>
                                <!-- Testo -->
                                <div class="card__text">
                                    At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
                                    vero eos et consectetur accus adip adip.
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Sfondo della carta -->
                                <img class="card__bg" src="../assets/img/quote.png" alt="Background">
                                <!-- Immagine della carta -->
                                <div class="card__image">
                                    <!-- Immagine -->
                                    <img class="card__image--img" src="../assets/img/27.jpeg" alt="Mac Znder">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Mac Znder <span class="card__title--title__little">- Manager Sofbox</span>
                                    </h3>
                                </div>
                                <!-- Testo -->
                                <div class="card__text">
                                    At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
                                    vero eos et consectetur accus adip adip.
                                </div>
                            </div>
                        </li>
                    </ul>
                    <!-- Pallini -->
                    <div class="dots">
                        <!-- Pallino -->
                        <div class="dot active">
                        </div>
                        <!-- Pallino -->
                        <div class="dot">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Testimonials */
    .testimonials {
        padding-top: 200px;
        position: relative;
    }
    /* Sfondo di testimonials */
    .testimonials__bg {
        background-color: var(--very-light-blue);
        width: 100%;
        height: 200px;
        position: absolute;
        left: 0px;
        top: 0px;
    }
    /* Box */
    .box {
        text-align: center;
        background: linear-gradient(to bottom, rgba(242, 247, 255, 1) 0, #ffffff 60%);
    }
    /* Titolo */
    .box__title {
        font-size: 36px;
        font-weight: normal;
        margin-bottom: 15px;
    }
    /* Testo */
    .box__text {
        margin-bottom: 100px;
        color: var(--grey);
    }
    /* Lista */
    .list {
        padding: 0px 30px;
        display: flex;
        gap: 60px;
    }
    /* Carta */
    .card {
        flex-basis: calc((100% / 2) - (60px * (1 / 2)));
        padding: 50px 0px;
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
        border-radius: 4px;
        position: relative;
    }
    /* Before della carta */
    .card::before {
        content: "";
        display: block;
        height: 10px;
        width: 90%;
        background-color: white;
        border-bottom-left-radius: 4px;
        border-bottom-right-radius: 4px;
        box-shadow: rgba(100, 100, 111, 1) 0px 7px 29px 0px;
        opacity: 0.3;
        position: absolute;
        left: 50%;
        bottom: -10px;
        transform: translate(-50%, 0%);
    }
    /* After della carta */
    .card::after {
        content: "";
        display: block;
        height: 10px;
        width: 80%;
        background-color: white;
        border-bottom-left-radius: 4px;
        border-bottom-right-radius: 4px;
        box-shadow: rgba(100, 100, 111, 1) 0px 7px 29px 0px;
        opacity: 0.1;
        position: absolute;
        left: 50%;
        bottom: -20px;
        transform: translate(-50%, 0%);
    }
    /* Sfondo della carta */
    .card__bg {
        width: 185px;
        position: absolute;
        top: 55%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    /* Immagine della carta */
    .card__image {
        margin-bottom: 45px;
        position: relative;
    }
    /* Immagine */
    .card__image--img {
        width: 65px;
        aspect-ratio: 1;
        border-radius: 999px;
    }
    /* Titolo della carta */
    .card__title {
        margin-bottom: 35px;
        position: relative;
    }
    /* Titolo */
    .card__title--title {
        font-weight: normal;
        font-size: 22px;
    }
    /* Scritta in piccolo del titolo */
    .card__title--title__little {
        font-size: 18px;
        color: var(--grey);
    }
    /* Testo della carta */
    .card__text {
        text-align: left;
        padding: 0px 30px;
        color: var(--grey);
        position: relative;
    }
    /* Pallini */
    .dots {
        margin-top: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5px;
    }
    /* Pallino */
    .dot {
        width: 10px;
        aspect-ratio: 1;
        background-color: black;
        border-radius: 999px;
        cursor: pointer;
    }
    /* Active */
    .dot.active {
        background-color: var(--blue);
    }
</style>