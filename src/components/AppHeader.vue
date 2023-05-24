<script>
export default {
    name: "AppHeader"
}
</script>

<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="navbar">
            <a href="">CHARACTERS</a>
            <a href="">COMICS</a>
            <a href="">MOVIES</a>
            <a href="">TV</a>
            <a href="">GAMES</a>
            <a href="">COLLECTIBLES</a>
            <a href="">VIDEOS</a>
            <a href="">FANS</a>
            <a href="">NEWS</a>
            <a href="">SHOP</a>
        </div>
    </header>
</template>

<style scoped>
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

