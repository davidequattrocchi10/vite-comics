<script>
export default {
    name: 'AppFooterBottom'

}
</script>

<template>
    <div class="footer-bottom">
        <div class="container">
            <div class="row container-bottom">

                <div>
                    <button>SIGN-UP NOW!</button>
                </div>
                <div class="follow-us">
                    <p>FOLLOW US</p>
                    <img src="/img/footer-facebook.png" alt="">
                    <img src="/img/footer-twitter.png" alt="">
                    <img src="/img/footer-youtube.png" alt="">
                    <img src="/img/footer-pinterest.png" alt="">
                    <img src="/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer-bottom {
    background-color: var(--color-footer);

    & .container-bottom {
        justify-content: space-between;
        align-items: center;
        min-height: 120px;
    }

    & button {
        border: 2px solid var(--menu-active);
        background-color: transparent;
        color: white;
        padding: 10px 15px;
        font-size: 16px;
        cursor: pointer;
        margin: 5px;
    }

    & .follow-us {
        display: flex;
        align-items: center;
        justify-content: space-around;
        gap: 15px;
        margin: 5px;

        & p {
            margin-right: 15px;
            color: var(--menu-active);
            font-size: larger;
            font-weight: bold;
        }

        & img {
            width: 35px;
            height: 35px;
        }
    }

}
</style>