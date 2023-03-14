<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Testimonials -->
    <section class="testimonials">
        <!-- Sfondo -->
        <img class="testimonials__bg" src="../assets/img/15.png" alt="Background">
        <!-- Container -->
        <div class="container">
            <!-- Box -->
            <div class="box">
                <!-- Titolo -->
                <h2 class="box__title">
                    Our Testimonials
                </h2>
                <!-- Testo -->
                <p class="box__text">
                    If you are planning on devoloping a product landing app or website,
                    take a look at this beautiful-crafted
                </p>
                <!-- Persone -->
                <div class="people">
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
                </div>
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Testimonials */
    .testimonials {
        position: relative;
    }
    /* Sfondo di testimonials */
    .testimonials__bg {
        background-color: var(--very-light-blue);
        width: 100%;
        height: 255px;
        position: absolute;
        left: 0px;
        top: 0px;
        z-index: -1;
    }
    /* Box */
    .box {
        text-align: center;
        padding-top: 113px;
    }
    /* Titolo */
    .box__title {
        font-size: 36px;
        font-weight: 500;
        margin-bottom: 15px;
    }
    /* Testo */
    .box__text {
        margin-bottom: 100px;
        color: var(--grey);
    }
    /* Persone */
    .people {
        padding: 0px 30px;
        display: flex;
        gap: 60px;
    }
    /* Carta */
    .card {
        flex-basis: calc((100% / 2) - (60px * (1 / 2)));
        padding: 50px 0px;
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
        position: relative;
    }
    /* Sfondo della carta */
    .card__bg {
        width: 250px;
        opacity: 0.1;
        position: absolute;
        top: 50%;
        left: 50%;
        z-index: -1;
        transform: translate(-50%, -50%);
    }
    /* Immagine della carta */
    .card__image {
        margin-bottom: 45px;
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
    }
</style>