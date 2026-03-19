<template>
    <div class="item pork" :class="{ expand: expanded }">
        <h2 class="d-flex justify-content-end mb-4 text-light title hov-glitch">Sobre Mi</h2>
        <p class="f-size text-light" :class="{'f-size': !expanded, 'fs-5': expanded, 'mt-4': expanded }">Soy desarrollador web y llegué a la programación de una forma bastante inesperada.
            Después de un accidente que me dejó en cama durante algunos meses, decidí aprovechar ese tiempo para
            aprender algo nuevo. Así fue como empecé con Python, simplemente por curiosidad...</p>

        <p class="fs-5" v-if="expanded">Con el tiempo me surgió una idea: crear una página donde mis amigos pudieran jugar a adivinar el videojuegPara hacerlo realidad tuve que aprender HTML, CSS y JavaScript, y fue ahí donde realmente me enganché con desarrollo web. <br><br>
        Después quise llevar ese proyecto un poco más lejos y automatizar algunas cosas, así que empecé a investigar sobre APIs y cómo conectar servicios entre sí. En ese proceso encontré el programa de Talento Digital, donde pude profundizar en distintas tecnologías y fortalecer mis habilidades como desarrollador. <br><br>
        Desde entonces he seguido construyendo proyectos, aprendiendo constantemente y mejorando mi forma de desarrollar. Me gusta crear cosas que funcionen bien, que se vean bien y que realmente aporten algo útil o entretenido.
        </p>

        <button @click="toggleExpanded" v-if="!expanded"
            class="btn btn-secondary position-fixed bottom-0 start-0 m-3 rounded-circle py-2">
                <i class="fa-solid fa-up-right-and-down-left-from-center"></i>
        </button>
        <button @click="toggleExpanded" v-if="expanded"
            class="btn btn-secondary position-fixed bottom-0 start-0 m-3 rounded-circle py-2">
                <i class="fa-solid fa-down-left-and-up-right-to-center"></i>
        </button>
    </div>

</template>

<script setup>
import { ref } from 'vue';

const expanded = ref(false);

const toggleExpanded = () => {
    expanded.value = !expanded.value;
}

</script>

<style scoped>
.f-size {
    font-size: 18px;
}



.item {
    position: relative;
    transition: transform .3s ease, width .3s ease, height .3s ease, top .3s ease, right .3s ease, box-shadow .3s ease, opacity .3s ease;
    transform-origin: top right;
}

.item.expand {

    
    position: absolute;
    top: 12%;
    right: 8%;
    width: 43%;
    height: 77%;
    z-index: 50;
    animation: growIn .35s ease forwards;
    box-shadow: 0 18px 40px #00000073;

}

@keyframes growIn {
    from {
        transform: scale(0.7);
        opacity: 1;
    }
    to {
        transform: scale(1);
        opacity: 1;
    }
}
</style>
