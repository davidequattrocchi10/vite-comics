<script>
export default {
    name: 'comicBook',
    props: {
        imgBook: String,
        textBook: String

    }

}
</script>

<template>
    <div class="book">
        <img :src="imgBook" alt="">
        <p>{{ textBook }}</p>
    </div>
</template>

<style scoped>
.book {
    height: 100%;
    width: 100%;

    &:hover {
        filter: drop-shadow(0 0 10px white);
    }

    & img {
        width: 100%;
        height: 80%;

    }

    & p {
        padding-top: 5px;
        font-size: small;
        height: 20%;
    }


}
</style>