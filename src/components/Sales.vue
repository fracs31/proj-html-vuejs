<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Sales -->
    <section class="sales">
        <!-- Container -->
        <div class="container">
            <!-- Box -->
            <div class="box">
                <!-- Descrizione -->
                <div class="box__description">
                    <!-- Titolo -->
                    <h2 class="box__description--title">
                        Get tips tricks on how to skyrocket
                        your sales.
                    </h2>
                    <!-- Testo -->
                    <p class="box__description--text">
                        Faff about only a quid blower I don't want no agro
                        bleeding chimney pot burke tosser cras nice one boot fanny.!
                    </p>
                    <!-- Lista -->
                    <ul class="tips">
                        <!-- Elemento della lista -->
                        <li class="tips__element">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta -->
                                <div class="card__image">
                                    <!-- Immagine -->
                                    <img class="card__image--img" src="../assets/img/510.png" alt="Analysis">
                                </div>
                                <!-- Descrizione della carta -->
                                <div class="card__description">
                                    <!-- Titolo -->
                                    <h3 class="card__description--title">
                                        Reporting Analysis
                                    </h3>
                                    <!-- Testo -->
                                    <p class="card__description--text">
                                        It is a long established fact that a reader will be distracted
                                        by the readable content of a page when looking at its layout.
                                    </p>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="tips__element">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta -->
                                <div class="card__image">
                                    <!-- Immagine -->
                                    <img class="card__image--img" src="../assets/img/511.png" alt="SEO">
                                </div>
                                <!-- Descrizione della carta -->
                                <div class="card__description">
                                    <!-- Titolo -->
                                    <h3 class="card__description--title">
                                        Technical SEO Audit
                                    </h3>
                                    <!-- Testo -->
                                    <p class="card__description--text">
                                        It is a long established fact that a reader will be distracted
                                        by the readable content of a page when looking at its layout.
                                    </p>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
                <!-- Immagine della box -->
                <div class="box__image">
                    <!-- Immagine -->
                    <img class="box__image--img" src="../assets/img/509.jpeg" alt="Sales">
                </div>
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Sales */
    .sales {
        padding-top: 165px;
    }
    /* Box */
    .box {
        display: flex;
        align-items: center;
        gap: 30px;
    }
    /* Titolo */
    .box__description--title {
        font-size: 36px;
        font-weight: normal;
        margin-bottom: 20px;
    }
    /* Testo */
    .box__description--text {
        margin-bottom: 40px;
        color: var(--grey);
    }
    /* Immagine usata */
    .box__image--img {
        width: 555px;
    }
    /* Elemento della lista */
    .tips__element {
        margin-bottom: 10px;
    }
    /* Carta */
    .card {
        display: flex;
        gap: 15px;
    }
    /* Titolo della prima carta */
    .tips__element:first-child .card {
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    }
    /* Descrizione della carta */
    .card__description {
        padding: 30px 0px;
    }
    /* Immagine della carta */
    .card__image {
        padding: 60px 15px;
    }
    /* Immagine utilizzata della carta */
    .card__image--img {
        width: 70px;
        aspect-ratio: 1;
    }
    /* Titolo della carta */
    .card__description--title {
        font-weight: 500;
        margin-bottom: 10px;
    }
    /* Titolo della prima carta */
    .tips__element:first-child .card .card__description--title {
        color: var(--blue);
    }
    /* Testo della carta */
    .card__description--text {
        color: var(--grey);
    }
</style>