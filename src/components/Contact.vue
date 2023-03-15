<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Contatti -->
    <section class="contact" id="contact">
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
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3152.433058493912!2d-122.47505588474775!3d37.803324279754165!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808586e6302615a1%3A0x86bd130251757c00!2sStorey%20Ave%2C%20San%20Francisco%2C%20CA%2094129%2C%20Stati%20Uniti!5e0!3m2!1sit!2sit!4v1678783196913!5m2!1sit!2sit" width="555" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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
    /* Contact */
    .contact {
        padding: 120px 0px;
    }
    /* Titolo del box */
    .box__title {
        font-size: 36px;
        font-weight: normal;
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
        font-weight: normal;
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
        cursor: pointer;
        transition: 0.3s;
    }
    /* Hover dei social */
    .social:hover {
        color: white;
        background-color: var(--blue);
        box-shadow: rgba(55, 125, 255, 1) 0px 8px 24px;
    }
    /* Get in touch */
    .get-in-touch {
        font-weight: normal;
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
        border-radius: 4px;
        padding: 10px;
        flex-basis: 100%;
        transition: border 1s;
    }
    /* Messaggio */
    .message {
        resize: vertical;
    }
    /* Input del form in hover */
    .form input:hover,
    .message:hover {
        border: 2px solid var(--blue);
    }
    /* Input del form in focus */
    .form input:focus,
    .message:focus {
        border: 2px solid var(--blue);
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
        transition: 0.8s;
    }
    /* Bottone in hover */
    .btn:hover {
        background-color: var(--first-black);
    }
</style>