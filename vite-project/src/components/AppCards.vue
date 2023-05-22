<script>
export default {
    name: "appCards",
    props: {
        cards: Array
    }
}
</script>

<template>
    <div>
        <AppCards :cards="cards" />
    </div>
    <!-- {{ cards }} -->
</template>