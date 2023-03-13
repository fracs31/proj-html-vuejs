<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Posts -->
    <section class="posts">
        <!-- Container -->
        <div class="container">
            <!-- Box -->
            <div class="box">
                <!-- Titolo -->
                <h2 class="box__title">
                    Latest Posts
                </h2>
                <!-- Testo -->
                <p class="box__text">
                    If you are planning on developing a product landing.
                </p>
                <!-- Lista -->
                <ul class="list">
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Immagine della carta -->
                            <div class="card__image">
                                <!-- Immagine -->
                                <img class="card__image--img" src="../assets/img/19.jpg" alt="Life Lack Meaning">
                                <!-- Data -->
                                <span class="date">
                                    November 28, 2019
                                </span>
                            </div>
                            <!-- Titolo della carta -->
                            <h3 class="card__title">
                                Life Lack Meaning
                            </h3>
                            <!-- Testo della carta -->
                            <p class="card__text">
                                It is a long established fact that a reader will be distracted
                                by the readable content of a page when looking at its layout.
                            </p>
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Immagine della carta -->
                            <div class="card__image">
                                <!-- Immagine -->
                                <img class="card__image--img" src="../assets/img/18.jpg" alt="Life Lack Meaning">
                                <!-- Data -->
                                <span class="date">
                                    November 28, 2019
                                </span>
                            </div>
                            <!-- Titolo della carta -->
                            <h3 class="card__title">
                                Life Lack Meaning
                            </h3>
                            <!-- Testo della carta -->
                            <p class="card__text">
                                It is a long established fact that a reader will be distracted
                                by the readable content of a page when looking at its layout.
                            </p>
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="list-item">
                        <!-- Carta -->
                        <div class="card">
                            <!-- Immagine della carta -->
                            <div class="card__image">
                                <!-- Immagine -->
                                <img class="card__image--img" src="../assets/img/17.jpg" alt="Life Lack Meaning">
                                <!-- Data -->
                                <span class="date">
                                    November 28, 2019
                                </span>
                            </div>
                            <!-- Titolo della carta -->
                            <h3 class="card__title">
                                Life Lack Meaning
                            </h3>
                            <!-- Testo della carta -->
                            <p class="card__text">
                                It is a long established fact that a reader will be distracted
                                by the readable content of a page when looking at its layout.
                            </p>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Box */
    .box {
        padding: 100px 0px;
    }
    .box__title {
        text-align: center;
        font-weight: normal;
        font-size: 36px;
        margin-bottom: 30px;
    }
    /* Testo */
    .box__text {
        text-align: center;
        color: var(--grey);
        padding-bottom: 105px;
    }
    /* Lista */
    .list {
        display: flex;
        gap: 30px;
    }
    /* Elemento della lista */
    .list-item {
        flex-basis: calc((100% / 3) - (30px * (2/ 3)));
    }
    /* Carta */
    .card {
        border: 1px solid var(--second-grey);
    }
    /* Immagine della carta */
    .card__image {
        position: relative;
        margin-bottom: 30px;
        padding: 10px;
    }
    /* Immagine usata per la carta */
    .card__image--img {
        width: 100%;
    }
    /* Data */
    .date {
        font-size: 14px;
        color: var(--grey);
        background-color: white;
        border: 1px solid var(--second-grey);
        border-radius: 4px;
        padding: 5px;
        position: absolute;
        top: 20px;
        left: 20px;
    }
    /* Titolo della carta */
    .card__title {
        margin-bottom: 15px;
        font-weight: 500;
        padding: 0px 30px;
    }
    /* Testo della carta */
    .card__text {
        color: var(--grey);
        padding: 0px 30px;
        margin-bottom: 20px;
    }
</style>