<script>
import AppMainBottom from './AppMainBottom.vue';

export default {
    name: 'AppMain',
    components: {
        AppMainBottom
    }

}
</script>

<template>
    <main>
        <div class="main-top">
            <p> --&gt; Content goes here &lt;-- </p>
        </div>
        <AppMainBottom></AppMainBottom>

    </main>
</template>

<style scoped>
main {

    & .main-top {
        padding: 1rem 12rem;
        color: white;
        display: flex;
        align-items: center;
        background-color: black;
        min-height: 150px;
        font-size: larger;
        font-weight: bold;
    }
}
</style>