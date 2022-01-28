<template>
    <div class="container">

        <div v-for="(card, index) in cards" :key="index" class="cards">
                <img :src="card.thumb"/>
                <h3>{{card.series}}</h3>
        </div>

    </div>
</template>

<script>
export default {
    props: {
        card: Array
    }
}
</script>

<style lang="scss" scoped>
@import './style/variables.scss';

    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        background-color: $background-darkgrey;
        height: 500px;

        .cards {
            width: 200px;
            height: 150px;
            background-color: red;
        }
    }
</style>