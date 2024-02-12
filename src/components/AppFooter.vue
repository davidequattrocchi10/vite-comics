<script>
import AppFooterTop from './AppFooterTop.vue';
import AppFooterBottom from './AppFooterBottom.vue';

export default {
    name: 'AppFooter',
    components: {
        AppFooterTop,
        AppFooterBottom
    }

}
</script>

<template>
    <footer>
        <AppFooterTop></AppFooterTop>
        <AppFooterBottom></AppFooterBottom>
    </footer>
</template>

<style scoped></style>