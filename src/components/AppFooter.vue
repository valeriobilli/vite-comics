<script>
export default {
    name: "AppFooter"
}
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="content-left">
                <a id="sign-up" href="">
                    <h3>SIGN-UP NOW!</h3>
                </a>
            </div>
            <div class="content-right">
                <a id="sign-up" href="">
                    <h3>FOLLOW US</h3>
                </a>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    height: 110px;
    background-color: #303030;
    color: white;
}

.content {
    width: 70%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.content-left {
    a {
        color: white;
        text-decoration: none;

        h3 {
            border: 2px solid #0282f9;
            padding: 0.8rem;
        }
    }
}

.content-right {
    display: flex;
    align-items: center;
    justify-content: space space-between;

    a {
        text-decoration: none;
        color: #0282f9;
    }

    img {
        margin-left: 1rem;
    }
}
</style>