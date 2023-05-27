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
                <a href="">DIGITAL COMICS</a>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <a href="">DC MERCHANDISE</a>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <a href="">SUBCRIPTION</a>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <a href="">COMIC SHOP LOCATOR</a>
            </div>
            <div class="link">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <a href="">DC POWER VISA</a>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
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

    img {
        height: 2rem;
        margin-right: 1rem;
        margin-left: 2rem;
    }

    a {
        text-decoration: none;
        color: white;
    }

}
</style>

