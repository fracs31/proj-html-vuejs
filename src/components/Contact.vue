<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Contatti -->
    <section class="contact">
        <!-- Container -->
        <div class="container">
            <!-- Box -->
            <div class="box">
                <!-- Titolo -->
                <h2 class="box__title">
                    Contact with our team
                </h2>
                <!-- Testo -->
                <p class="box__text">
                    If you are planning on developing a product landing.
                </p>
                <!-- Informazioni -->
                <div class="informations">
                    <!-- Mappa -->
                    <div class="map">
                        <!-- Immagine -->
                        <img class="map__img" src="../assets/img/StaticMapService.GetMapIma.png" alt="Map">
                    </div>
                    <!-- Noi -->
                    <div class="us">
                        <!-- Immagine -->
                        <img class="us__image" src="../assets/img/35.png" alt="Us">
                        <!-- Indirizzo -->
                        <h3 class="address">
                            9840 Shore St. Fond Du Lac, WI 54935
                        </h3>
                        <!-- Telefono -->
                        <p class="phone">
                            0 1223 456 789
                        </p>
                        <!-- Email -->
                        <p class="email">
                            mail@sofbox.com
                        </p>
                        <!-- Socials -->
                        <ul class="socials">
                            <!-- Social -->
                            <li class="social">
                                <i class="fa-brands fa-facebook-f"></i>
                            </li>
                            <!-- Social -->
                            <li class="social">
                                <i class="fa-brands fa-twitter"></i>
                            </li>
                            <!-- Social -->
                            <li class="social">
                                <i class="fa-brands fa-github"></i>
                            </li>
                            <!-- Social -->
                            <li class="social">
                                <i class="fa-brands fa-instagram"></i>
                            </li>
                        </ul>
                        <!-- Get in touch -->
                        <h3 class="get-in-touch">
                            Get in Touch
                        </h3>
                        <!-- Form -->
                        <form class="form">
                            <!-- Nome -->
                            <input class="name" type="text" placeholder="Your Name">
                            <!-- Email -->
                            <input class="mail" type="email" placeholder="Your Email">
                            <!-- Argomento -->
                            <input class="subject" type="text" placeholder="Your Subject">
                            <textarea class="message" cols="30" rows="10" placeholder="Your Message"></textarea>
                            <!-- Bottone -->
                            <button class="btn">
                                Send message
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<!-- CSS -->
<style scoped>
    /* Box */
    .box {
        padding: 120px 0px;
    }
    /* Titolo del box */
    .box__title {
        font-size: 36px;
        font-weight: 500;
        text-align: center;
        margin-bottom: 30px;
    }
    /* Testo del box */
    .box__text {
        text-align: center;
        color: var(--grey);
        margin-bottom: 105px;
    }
    /* Informazioni */
    .informations {
        display: flex;
        gap: 30px;
    }
    /* Immagine della mappa */
    .map__image {
        width: 555px;
    }
    /* Immagine di us */
    .us__image {
        width: 125px;
        margin-bottom: 40px;
    }
    /* Indirizzo */
    .address {
        font-weight: 500;
        font-size: 22px;
        margin-bottom: 25px;
    }
    /* Telefono */
    .phone {
        color: var(--grey);
        margin-bottom: 15px;
    }
    /* Email */
    .email {
        color: var(--grey);
        margin-bottom: 55px;
    }
    /* Socials */
    .socials {
        margin-bottom: 35px;
        display: flex;
        gap: 10px;
    }
    /* Social */
    .social {
        color: var(--blue);
        width: 40px;
        aspect-ratio: 1;
        text-align: center;
        line-height: 40px;
        border: 1px solid var(--second-grey);
        border-radius: 4px;
    }
    /* Get in touch */
    .get-in-touch {
        font-weight: 500;
        font-size: 22px;
        margin-bottom: 30px;
    }
    /* Form */
    .form {
        display: flex;
        align-items: flex-start;
        flex-wrap: wrap;
        gap: 30px 30px;
    }
    /* Input del form */
    .form input,
    .message {
        font-size: 14px;
        border: 1px solid var(--second-grey);
        padding: 10px;
        flex-basis: 100%;
    }
    /* Nome del form e mail del form */
    .form .name,
    .form .mail {
        flex-basis: calc((100% / 2) - (30px * (1 / 2)));
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
        width: fit-content;
    }
</style>