<template>
    <div>
        <button>SIGN-UP NOW!</button>
        <nav>
            <ul>
                <li>FOLLOW US</li>
                <li>
                    <img src="@/assets/footer-facebook.png">
                </li>
                <li>
                    <img src="@/assets/footer-twitter.png">
                </li>
                <li>
                    <img src="@/assets/footer-youtube.png">
                </li>
                <li>
                    <img src="@/assets/footer-pinterest.png">
                </li>
                <li>
                    <img src="@/assets/footer-periscope.png">
                </li>
                
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import './style/variables.scss';

div {
    background-color: $background-grey;
    height: 100px;
    display: flex;
    justify-content: space-around;
    align-items: center;

    button {
    cursor: pointer;
    text-align: center;
    outline: none;
    text-decoration: none;
    padding: 10px 20px;
    border: 3px $background-blu solid;
    color: $text-white-color;
    background-color: $background-grey;
    font-weight: bold;
    }

    nav {
        ul {
            display: flex;
            list-style: none;

            li{
                padding: 10px;
            }

            li:first-child {
                color: $text-blu-color;
                font-weight: bold;
                font-size: 25px;
            }
        }
    }
}
</style>