<template>
    <div class="app-container">
        <MainBackground class="shader-bg" :scale="1.2" :mouseInfluence="0.8" :transparent="false" :colors="['#0a0a0a', '#111111', '#181818']" />

        <div class="wrapper content-layer">
            <div class="bento-grid line-link">
                <Me />
                <MeImg />
                <Tecnologies />
                <AboutMe />
                <AppProyects />
                <Form />
                <Social />
            </div>
        </div>
    </div>
</template>

<script setup>
import AboutMe from './AboutMe.vue';
import Me from './Me.vue'
import MeImg from './MeImg.vue';
import Tecnologies from './Tecnologies.vue';
import AppProyects from './AppProyects.vue';
import Social from './Social.vue';
import Form from './Form.vue';
import MainBackground from './MainBackground.vue';
</script>

<style scoped>
.app-container {
    position: relative;
    width: 100vw;
    height: 100vh;
    overflow: hidden;
    background: #000;
}

.shader-bg {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    z-index: 0;
    pointer-events: none;
}

.content-layer {
    position: relative;
    z-index: 1;
    width: 100%;
    height: 100%;
}
</style>