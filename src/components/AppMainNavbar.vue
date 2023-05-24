<script>
export default {
    name: "AppMainNavbar"
}
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="link">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                DIGITAL COMICS
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                DC MERCHANDISE
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                SUBCRIPTION
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                COMIC SHOP LOCATOR
            </div>
            <div class="link">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                DC POWER VISA
            </div>
        </div>


    </div>
</template>

<style scoped>
.container {
    height: 155px;
    background-color: #0282f9;
    color: white;
    display: flex;
    align-items: center;

}

.content {
    width: 70%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.link {
    display: flex;
    align-items: center;
    font-size: 0.8rem;
}

.link>img {
    height: 2rem;
    margin-right: 1rem;
    margin-left: 2rem;
}
</style>

