<script>
export default {
    name: 'AppFooterTop'

}
</script>

<template>
    <div class="footer-top">
        <div class="row">
            <div class="col">
                <h3>DC COMICS</h3>
                <ul class="list-unstyled">
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li><a href="">Movies</a></li>
                    <li><a href="">TV </a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Videos</a></li>
                    <li><a href="">News</a></li>
                </ul>
                <h3>SHOP</h3>
                <ul class="list-unstyled">
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="col">
                <h3>DC</h3>
                <ul class="list-unstyled">
                    <li><a href="">Terms of Use</a></li>
                    <li><a href="">Privacy policy (New)</a></li>
                    <li><a href="">Ad Choices</a></li>
                    <li><a href="">Advertising</a></li>
                    <li><a href="">Jobs</a></li>
                    <li><a href="">Subscriptions</a></li>
                    <li><a href="">Talent Workshops</a></li>
                    <li><a href="">CPSC Certificates</a></li>
                    <li><a href="">Ratings</a></li>
                    <li><a href="">Shop Help</a></li>
                    <li><a href="">Contact Us</a></li>
                </ul>
            </div>
            <div class="col">
                <h3>SITES</h3>
                <ul class="list-unstyled">
                    <li><a href="">DC</a></li>
                    <li><a href="">MAD Magazine</a></li>
                    <li><a href="">DC Kids</a></li>
                    <li><a href="">DC Universe</a></li>
                    <li><a href="">DC Power Visa</a></li>
                </ul>
            </div>
            <div class="col">
                <img src="/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer-top {
    padding-top: 2rem;
    height: 350px;
    background-image: url(/img/footer-bg.jpg);
    overflow: hidden;

    & h3 {
        color: white;
        margin-bottom: 1rem;
    }

    & ul.list-unstyled {
        list-style: none;

        & a {
            text-decoration: none;
            color: var(--footer-menu-text);
            font-size: small;
        }
    }
}

.row {
    display: flex;
    padding: 10px 12rem;
    position: relative;
}

.col {
    margin-right: 20px;

    & img {
        width: 32%;
        position: absolute;
        top: -8rem;
        left: 57rem;
    }
}
</style>