<script>
export default {
    name: 'AppMainBottom'

}
</script>


<template>
    <div class="main-bottom">
        <div class="image-item">
            <img src="/img/buy-comics-digital-comics.png" alt="Image 1">
            <div class="image-caption">DIGITAL COMICS</div>
        </div>
        <div class="image-item">
            <img src="/img/buy-comics-merchandise.png" alt="Image 2">
            <div class="image-caption">DC MERCHANDISE</div>
        </div>
        <div class="image-item">
            <img src="/img/buy-comics-subscriptions.png" alt="Image 3">
            <p class="image-caption">SUBSCRIPTION</p>
        </div>
        <div class="image-item">
            <img src="/img/buy-comics-shop-locator.png" alt="Image 4">
            <div class="image-caption">COMIC SHOP LOCATOR</div>
        </div>
        <div class="image-item">
            <img src="/img/buy-dc-power-visa.svg" alt="Image 5">
            <div class="image-caption">DC POWER VISA</div>
        </div>
    </div>
</template>



<style scoped>
.main-bottom {
    padding: 1rem 12rem;
    color: white;
    display: flex;
    background-color: var(--menu-active);
    min-height: 150px;


    & .image-item {
        margin-left: 50px;
        display: flex;
        flex-wrap: nowrap;
        align-items: center;

        & img {
            width: 50px;
            height: 60px;
        }

        & .image-caption {
            font-size: small;
            margin: 10px;
            padding: 10px;
        }
    }



}
</style>