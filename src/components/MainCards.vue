<template>
    <main>
        <button class="button-series">CURRENT SERIES</button>

        <div class="container">
            

            <div v-for="(card, index) in card" :key="index" class="card">
                <img :src="card.thumb"/>
                <span>{{card.series}}</span>
            </div>

        </div>

        <button>LOAD MORE</button>
    </main>
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

    main {
        background-color: $background-darkgrey;
        color: $text-white-color;
        padding: 70px 0;
        text-align: center;

        .container {
            width: 1200px;
            height: 700px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;


            .card {
                width: 15%;
                padding: 15px;
                text-align: center;

                img {
                    width: 100%;
                }
            }
        }

        button {
        cursor: pointer;
        text-align: center;
        outline: none;
        text-decoration: none;
        border-style: hidden;
        padding: 10px 45px;
        color: $text-white-color;
        background-color: $background-blu;
        font-weight: bold;
        }

        .button-series{
            padding: 15px;
            font-size: 25px;
            position: absolute;
            top: 320px;
            left: 50px;
        }
    }


</style>