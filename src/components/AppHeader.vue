<script>
import { CompilerDeprecationTypes } from '@vue/compiler-core';

export default {
    name: "AppHeader",

    data() {
        return {
            navLinks: [
                "CHARACTERS",
                "COMICS",
                "MOVIES",
                "TV",
                "GAMES",
                "COLLECTIBLES",
                "VIDEOS",
                "FANS",
                "NEWS",
                "SHOP"
            ]
        }

    }
}
</script>

<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="navbar">
            <a v-for="link in navLinks">{{ link }}</a>
        </div>
    </header>
</template>

<style scoped lang="scss">
header {
    height: 120px;
    background-color: white;
    width: 70%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar {
    display: flex;
}

.navbar>a {
    margin-right: 1rem;
    text-decoration: none;
    color: black;
}
</style>

