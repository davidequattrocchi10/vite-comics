<script>
export default {
    name: 'AppFooterBottom'

}
</script>

<template>
    <div class="footer-bottom">
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
</template>

<style scoped>
.footer-bottom {
    min-height: 120px;
    background-color: var(--color-footer);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 12rem;

    & button {
        border: 2px solid var(--menu-active);
        background-color: transparent;
        color: white;
        padding: 10px 15px;
        font-size: 16px;
        cursor: pointer;
    }

    & .follow-us {
        display: flex;
        align-items: center;
        justify-content: space-around;
        gap: 15px;

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