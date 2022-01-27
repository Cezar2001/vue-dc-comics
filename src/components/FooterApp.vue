<template>
    <div class="background">

        <div class="list">
            <ul>
                <li>
                    <h2>DC COMICS</h2>
                </li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
                <li>
                    <h2>SHOP</h2>
                </li>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
        </div>

        <div class="list">
            <ul>
                <li>
                    <h2>DC</h2>
                </li>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Rating</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
        </div>

        <div class="list">
            <ul>
                <li>
                    <h2>SITES</h2>
                </li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>

        <div class="logo"></div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import './style/variables.scss';

.background {
    background-image: url('../assets/footer-bg.jpg');
    height: 420px;
    display: flex;
    justify-content: space-around;

    .list {
        margin-top: 15px;
        ul {
            list-style: none;

            li {
                color: $text-grey-color;
                padding: 5px 0;

                h2 {
                    color: $text-white-color;
                    padding: 10px 0;
                }
            }
        }
    }

    .logo {
        background-image: url('../assets/dc-logo-bg.png');
        background-size: cover;
        width: 500px;
    }
}
</style>