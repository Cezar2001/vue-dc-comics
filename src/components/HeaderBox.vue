<template>
    <header>
        <div class="logo">
            <img src="@/assets/dc-logo.png"/>
        </div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import './style/variables.scss';

header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100px;

    img{
        width: 70px;
        height: 70px;
    }

    nav {
        ul {
            list-style: none;
            display: flex;
            justify-content: center;

            li {
                padding: 35px 10px;
                cursor: pointer;

                &:hover {
                    color: $text-blu-color;
                    border-bottom: 5px $text-blu-color solid;
                }
            }
        }
    }
}
</style>