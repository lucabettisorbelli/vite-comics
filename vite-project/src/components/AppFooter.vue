<script>
export default {
    name: "AppFooter"
}
</script>

<template>
    <footer>
        <div class="containerLinks">
            <div class="boxedContainer d-flex ">
                <div class="boxDcShop p-1">
                    <div class="boxMargin">

                    </div>
                    <div class="titleDcComics p-1">
                        <span>DC COMICS</span>
                        <ul class="list-none">
                            <li>Characte</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div class="shop">
                        <div class="titleShop p-1">
                            <span>SHOP</span>
                        </div>
                        <ul class="list-none">
                            <li>DC</li>
                            <li>DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <div class="dc p-1">
                    <div class="titleDc p-1">
                        <span>DC</span>
                    </div>
                    <ul class="list-none">
                        <li>Terms Of use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choice:</li>
                        <li>Advertising</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact</li>
                    </ul>
                </div>
                <div class="sites p-1">
                    <div class="titleSites p-1">
                        <span>SITES</span>
                    </div>
                    <ul class="list-none">
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
                <div class="imageDc">

                </div>
            </div>
        </div>

        <div class="containerLoghi">
            <div class="boxedLoghi d-flex justify-space-between align-items-center">
                <div class="boxButton">
                    <button class="btn">SIGN UP NOW!</button>
                </div>
                <div class="boxFollowed d-flex">
                    <div class="titleFollowed d-flex align-items-center ">
                        <span>FOLLOW US</span>
                    </div>
                    <div class="loghiFollowed d-flex p-1">
                        <div class="p-1">
                            <img src="/footer-facebook.png" alt="">
                        </div>
                        <div class="p-1">
                            <img src="/footer-periscope.png" alt="">
                        </div>
                        <div class="p-1">
                            <img src="/footer-pinterest.png" alt="">
                        </div>
                        <div class="p-1">
                            <img src="/footer-twitter.png" alt="">
                        </div>
                        <div class="p-1">
                            <img src="/footer-youtube.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
.containerLinks {
    background-image: url(/footer-bg.jpg);
    height: 40vh;
    color: white;
}

.boxedContainer {
    max-width: 1200px;
    margin: 0 auto;
    height: 100%;
}

.boxedLoghi {
    max-width: 1200px;
    margin: 0 auto;
    height: 100%;
}

.containerLoghi {
    height: 15vh;
    background-color: #303030;
}

.btn {
    padding: 0.8rem;
    border: 1px solid lightblue;
    background-color: transparent;
    color: white;
}

.titleFollowed {
    color: #0282f9;
}

.imageDc {
    height: 100%;
    width: 100%;
    background-image: url(/dc-logo-bg.png);
    background-size: cover;
    background-position: 30% 70%;
}
</style>
