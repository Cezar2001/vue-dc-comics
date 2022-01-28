<template>
    <header>
        <div class="logo">
            <img src="@/assets/dc-logo.png"/>
        </div>
        <nav>
            <ul>
                <li v-for="link in nav" :key="link.id">
                    <a :href="link.url">
                        {{link.label}}
                    </a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    props: {
        nav: Array
    } 
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
                    border-bottom: 5px $background-blu solid;
                }

                a {
                    text-decoration: none;
                    font-weight: bold;
                }
            }
        }
    }
}
</style>