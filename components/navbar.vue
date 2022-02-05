<template>
    <div class="navbar">
        <v-btn small text class="mt-2 ml-10">Continuer sur sideral.is</v-btn>
        <!-- <v-btn class="float-right mt-3 mr-10" x-small text>Langage</v-btn> -->
    </div>
</template>

<script>
export default {
    name: 'navbar'
}
</script>

<style>
.navbar {
    height: 45px;
    width: 100%;
    background-color: #000;
    z-index: 1000;
}
</style>