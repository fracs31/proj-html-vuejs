<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Footer -->
    <footer class="page-footer">
        <!-- Container -->
        <div class="container">
            <!-- Box -->
            <div class="box">
                <!-- Ultime informazioni -->
                <div class="last-informations">
                    <!-- Logo -->
                    <img class="last-informations__image" src="../assets/img/35.png" alt="Logo">
                    <!-- Testo -->
                    <p class="last-informations__text">
                        It is a long established fact that a reader will be distracted
                        by the readable content.
                    </p>
                    <!-- Copyright -->
                    <p class="last-informations__copyright">
                        Copyright @ 2018 <span class="last-informations__copyright--blue">Sofbox</span>
                    </p>
                </div>
                <!-- Contenuto -->
                <div class="content">
                    <!-- Informazione -->
                    <div class="info">
                        <!-- Titolo dell'informazione -->
                        <h4 class="info__title">
                            Menu
                        </h4>
                        <!-- Lista -->
                        <ul class="list">
                            <!-- Elemento della lista -->
                            <li class="list-item">About Us</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Theme</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Features</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Pricing</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Blog</li>
                        </ul>
                    </div>
                    <!-- Informazione -->
                    <div class="info">
                        <!-- Titolo dell'informazione -->
                        <h4 class="info__title">
                            About Us
                        </h4>
                        <!-- Lista -->
                        <ul class="list">
                            <!-- Elemento della lista -->
                            <li class="list-item">About Sofbox</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Roadmap</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">How it Work</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Team</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">News</li>
                        </ul>
                    </div>
                    <!-- Informazione -->
                    <div class="info">
                        <!-- Titolo dell'informazione -->
                        <h4 class="info__title">
                            Menu
                        </h4>
                        <!-- Lista -->
                        <ul class="list">
                            <!-- Elemento della lista -->
                            <li class="list-item">About Us</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Theme</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Features</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Pricing</li>
                            <!-- Elemento della lista -->
                            <li class="list-item">Blog</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<!-- CSS -->
<style scoped>
    /* Footer */
    .page-footer {
        padding-top: 70px;
        padding-bottom: 90px;
        border-top: 1px solid var(--second-grey);
    }
    /* Box */
    .box {
        display: flex;
        gap: 80px;
    }
    /* Ultime informazioni */
    .last-informations {
        width: 250px;
    }
    /* Immagine */
    .last-informations__image {
        width: 145px;
        margin-bottom: 20px;
    }
    /* Testo*/
    .last-informations__text {
        color: var(--grey);
        margin-bottom: 70px;
    }
    /* Copyright */
    .last-informations__copyright {
        color: var(--grey);
    }
    /* Blue */
    .last-informations__copyright--blue {
        color: var(--blue);
    }
    /* Contenuto */
    .content {
        flex-grow: 1;
        display: flex;
        justify-content: space-around;
    }
    /* Titolo della lista */
    .info__title {
        margin-bottom: 25px;
        font-weight: normal;
        font-size: 20px;
    }
    /* Elementi della lista */
    .list-item {
        color: var(--grey);
        margin-bottom: 25px;
        cursor: pointer;
        transition: 0.5s;
    }
    /* Elementi della lista in hover */
    .list-item:hover {
        color: var(--blue);
    }
</style>