<script>
export default {
    name: "AppLinks"
}
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="content-left">
                <div class="column">
                    <h3>DC COMICS</h3>
                    <div>Characters</div>
                    <div>Comics</div>
                    <div>Movies</div>
                    <div>TV</div>
                    <div>Games</div>
                    <div>Videos</div>
                    <div>News</div>
                </div>
                <div class="column">
                    <h3>SHOP</h3>
                    <div>Shop DC</div>
                    <div>Shop DC Collectibles</div>
                </div>
                <div class="column">
                    <h3>DC</h3>
                    <div>Terms Of Use</div>
                    <div>Privacy Policy (New)</div>
                    <div>Ad Choices</div>
                    <div>Advertising</div>
                    <div>Jobs</div>
                    <div>Subscriptions</div>
                    <div>Talent Workshops</div>
                    <div>CPSC Certificates</div>
                    <div>Ratings</div>
                    <div>Shop Help</div>
                    <div>Contact Us</div>
                </div>
                <div class="column">
                    <h3>SITES</h3>
                    <div>DC</div>
                    <div>MAD Magazine</div>
                    <div>DC Kids</div>
                    <div>DC Universe</div>
                    <div>DC Power Visa</div>
                </div>
            </div>
            <div class="content-right">
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    height: 370px;
    background-image: url(../assets/img/footer-bg.jpg);
    color: white;
}

.content {
    width: 70%;
    height: 370px;
    margin: 0 auto;
    display: flex;
}

.content-left {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;

    .column {
        width: calc(100% / 3);
        margin-top: 2rem;

        div {
            margin: 0.6rem 0;
            font-size: 0.7rem;
            color: gray;
        }
    }
}

.content-right {
    width: 50%;
    height: 100%;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-position: center;
    background-size: cover;
}
</style>