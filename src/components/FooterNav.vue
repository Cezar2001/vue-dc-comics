<template>
    <nav>
        <ul>
        <li>
            <img src="@/assets/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
        </li>
        <li>
            <img src="@/assets/buy-comics-merchandise.png" alt="">
            <span>DC MERCHANDISE</span>
        </li>
        <li>
            <img src="@/assets/buy-comics-shop-locator.png" alt="">
            <span>SUBSCRIPTION</span>
        </li>
        <li>
            <img src="@/assets/buy-comics-subscriptions.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
        </li>
        <li>
            <img src="@/assets/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
        </li>
        </ul>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import './style/variables.scss';
    nav {
        background-color: $background-blu;
        height: 120px;
        line-height: 120px;
        
        ul {
            list-style: none;
            display: flex;
            justify-content: space-around;

            
            li {
                display: flex;
                align-items: center;
                color: $text-white-color;

                img {
                    width: 40px;
                    height: 40px;
                }

                span {
                    margin-left: 10px;
                }
            }
        }
    }
</style>