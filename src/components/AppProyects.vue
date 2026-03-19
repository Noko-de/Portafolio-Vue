<template>
    <div id="carouselExampleCaptions" class="item edamame carousel slide">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3"
                aria-label="Slide 4"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4"
                aria-label="Slide 5"></button>
        </div>
        <div class="carousel-inner ">
            <div class="carousel-item active ">
                <div class="card glitch-card ">
                    <img src="../assets/img/proyecto_clima.png" class="card__img d-block w-100 h-100 object-fit-cover ">

                    <div class="card__content ">
                        <p class="card__title">App de CLima</p>
                        <p class="card__description">
                            Proyecto enfocado en el aprendisaje de uso de API, usando la API Open weather map y
                            uso basico de JavaScript
                        </p>
                        <a href="https://noko-de.github.io/weather-app/" target="_blank">
                            <button class="glow-btn">Ir al proyecto</button>
                        </a>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card">
                    <img src="../assets/img/web_1.webp " class="d-block  w-100 h-100 object-fit-cover"
                        viewBox="0 0 24 24">
                    <path
                        d="M20 5H4V19L13.2923 9.70649C13.6828 9.31595 14.3159 9.31591 14.7065 9.70641L20 15.0104V5ZM2 3.9934C2 3.44476 2.45531 3 2.9918 3H21.0082C21.556 3 22 3.44495 22 3.9934V20.0066C22 20.5552 21.5447 21 21.0082 21H2.9918C2.44405 21 2 20.5551 2 20.0066V3.9934ZM8 11C6.89543 11 6 10.1046 6 9C6 7.89543 6.89543 7 8 7C9.10457 7 10 7.89543 10 9C10 10.1046 9.10457 11 8 11Z">
                    </path></img>
                    <div class="card__content ">
                        <p class="card__title">Card Title</p>
                        <p class="card__description">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        </p>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card">
                    <img src="../assets/img/web_3.webp" class="d-block  w-100 h-100 object-fit-cover"
                        viewBox="0 0 24 24">
                    <path
                        d="M20 5H4V19L13.2923 9.70649C13.6828 9.31595 14.3159 9.31591 14.7065 9.70641L20 15.0104V5ZM2 3.9934C2 3.44476 2.45531 3 2.9918 3H21.0082C21.556 3 22 3.44495 22 3.9934V20.0066C22 20.5552 21.5447 21 21.0082 21H2.9918C2.44405 21 2 20.5551 2 20.0066V3.9934ZM8 11C6.89543 11 6 10.1046 6 9C6 7.89543 6.89543 7 8 7C9.10457 7 10 7.89543 10 9C10 10.1046 9.10457 11 8 11Z">
                    </path></img>
                    <div class="card__content">
                        <p class="card__title">Card Title</p>
                        <p class="card__description">Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
                            veniam, quis nostrud exercitation ullamco.</p>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card">
                    <img src="../assets/img/web_4.webp" class="d-block  w-100 h-100 object-fit-cover"
                        viewBox="0 0 24 24">
                    <path
                        d="M20 5H4V19L13.2923 9.70649C13.6828 9.31595 14.3159 9.31591 14.7065 9.70641L20 15.0104V5ZM2 3.9934C2 3.44476 2.45531 3 2.9918 3H21.0082C21.556 3 22 3.44495 22 3.9934V20.0066C22 20.5552 21.5447 21 21.0082 21H2.9918C2.44405 21 2 20.5551 2 20.0066V3.9934ZM8 11C6.89543 11 6 10.1046 6 9C6 7.89543 6.89543 7 8 7C9.10457 7 10 7.89543 10 9C10 10.1046 9.10457 11 8 11Z">
                    </path></img>
                    <div class="card__content">
                        <p class="card__title">Card Title</p>
                        <p class="card__description">Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
                            veniam, quis nostrud exercitation ullamco.</p>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <div class="card">
                    <img src="../assets/img/web_5.webp" class="d-block  w-100 h-100 object-fit-cover"
                        viewBox="0 0 24 24">
                    <path
                        d="M20 5H4V19L13.2923 9.70649C13.6828 9.31595 14.3159 9.31591 14.7065 9.70641L20 15.0104V5ZM2 3.9934C2 3.44476 2.45531 3 2.9918 3H21.0082C21.556 3 22 3.44495 22 3.9934V20.0066C22 20.5552 21.5447 21 21.0082 21H2.9918C2.44405 21 2 20.5551 2 20.0066V3.9934ZM8 11C6.89543 11 6 10.1046 6 9C6 7.89543 6.89543 7 8 7C9.10457 7 10 7.89543 10 9C10 10.1046 9.10457 11 8 11Z">
                    </path></img>
                    <div class="card__content">
                        <p class="card__title">Card Title</p>
                        <p class="card__description">Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
                            veniam, quis nostrud exercitation ullamco.</p>
                    </div>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>

<script setup>
import AppMainPage from '../components/AppMainPage.vue';


</script>

<style scoped></style>
