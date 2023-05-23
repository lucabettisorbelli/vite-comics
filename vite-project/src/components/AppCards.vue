<script>
export default {
    name: "appCards",
    props: {
        cards: Array
    }
}
</script>

<template>
    <div class="container">
        <div class="containerCards">
            <div v-for="card in cards" class="card">
                <div class="imgCard">
                    <img :src="card.thumb" alt="">
                </div>
                <div class="textCard">
                    <span>
                        <span>{{ card.series }}</span>
                    </span>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.containerCards {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    align-items: baseline;
    flex-wrap: wrap;
    margin-top: 50px;
}

.card {
    width: calc(100% / 6);
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    padding: 10px;
}

.imgCard {
    height: 200px;
}

.imgCard img {
    width: 100%;
    height: 100%;
}
</style>