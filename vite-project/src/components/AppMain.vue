<script>
export default {
    name: "AppMain",
    data() {
        return {
            elements: [
                {
                    logo: `/public/buy-comics-digital-comics.png`,
                    text: 'DIGITAL COMICS',
                },
                {
                    logo: `/public/buy-comics-merchandise.png`,
                    text: 'DC MERCHANDISE',
                },
                {
                    logo: `/public/buy-comics-shop-locator.png`,
                    text: 'SUBSCRIPTION',
                },
                {
                    logo: `/public/buy-comics-subscriptions.png`,
                    text: 'COMIC SHOP LOCATOR',
                },
                {
                    logo: `/public/buy-comics-digital-comics.png`,
                    text: 'DC POWER VISA',
                },
            ]
        }
    }
}
</script>
<template>
    <main>
        <div class="containerTop">
            <div class="boxedTop d-flex align-items-center">
                <h3>__>Content goes here </h3>
            </div>
        </div>
        <div class="containerBottom">
            <div class="boxedBottom d-flex align-items-center justify-space-between">
                <div v-for="element in elements" class="elementSrc">
                    <div class="imgLogo">
                        <img :src="element.logo" alt="Logo">
                    </div>
                    <div class="imgText">
                        {{ element.text }}
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>


<style scoped>
.boxedTop,
.boxedBottom {
    max-width: 1200px;
    margin: 0 auto;
    height: 15vh;
    color: white;
}

.containerTop {
    background-color: #1c1c1c;
}

.containerBottom {
    background-color: #0282f9;
    height: 15vh;
}
</style>