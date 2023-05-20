
<script>
export default {
    name: "AppMain",
    data() {
        return {
            elements: [
                {
                    logo: "../assets/buy-comics-digital-comics.png",
                    text: 'bbb',
                },
                {
                    logo: "../assets/buy-merchandasing.png",
                    text: 'bbnnnb',
                },
                {
                    logo: "../assets/buy-comics-shop-locator.png",
                    text: 'bbnnnb',
                },
                {
                    logo: "../assets/buy-comics-subscription.png",
                    text: 'bbnnnb',
                },
                {
                    logo: "../assets/buy-comics-digital-comics.png",
                    text: 'bbnnnb',
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
            <div class="boxedBottom d-flex align-items-center">
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
    background-color: black;
}

.containerBottom {
    background-color: aqua;
    height: 15vh;
}
</style>