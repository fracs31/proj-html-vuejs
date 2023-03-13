<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Hero -->
    <section class="hero">
        <!-- Box -->
        <div class="box">
            <!-- Descrizione della box -->
            <div class="box__description">
                <!-- Titolo -->
                <h1 class="box__description--title">
                    The biggest platform for your growth.
                </h1>
                <!-- Testo -->
                <p class="box__description--text">
                    There are many variations of passages of Lorem Ipsum available,
                    but the majority have suffered alteration in some form
                </p>
                <!-- Bottone -->
                <button class="box__description--btn btn">
                    Read More
                </button>
            </div>
            <!-- Immagine della box -->
            <div class="box__image">
                <!-- Immagine -->
                <img class="box__image--img" src="../assets/img/508.jpeg" alt="Hero">
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Hero */
    .hero {
        padding: 10px 150px;
    }
    /* Box */
    .box {
        background-color: var(--very-light-blue);
        border-radius: 6px;
        padding: 60px;
        display: flex;
        gap: 60px;
    }
    /* Titolo */
    .box__description--title {
        font-weight: normal;
        font-size: 42px;
        margin-bottom: 30px;
    }
    /* Testo */
    .box__description--text {
        font-size: 14px;
        margin-bottom: 40px;
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
    /* Immagine usata */
    .box__image--img {
        width: 700px;
        display: block;
        margin-bottom: -160px;
        margin-top: -40px;
    }
</style>