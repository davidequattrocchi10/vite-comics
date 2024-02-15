<script>
export default {
    name: 'AppFooterTop'

}
</script>

<template>
    <div class="footer-top">
        <div class="container">
            <div class="row">
                <div class="col-md-4  col-lg-1">
                    <h6>DC COMICS</h6>
                    <ul class="list-unstyled">
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV </a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                    <h6>SHOP</h6>
                    <ul class="list-unstyled">
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="col-md-4  col-lg-1">
                    <h6>DC</h6>
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
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="col-md-4  col-lg-1">
                    <h6>SITES</h6>
                    <ul class="list-unstyled">
                        <li><a href="">DC</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>
                    </ul>
                </div>
                <div class="col-md-4 col-lg-1 image desktop-only">
                    <img src="/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer-top {
    padding-top: 2rem;
    min-height: 350px;
    background-image: url(/img/footer-bg.jpg);
    overflow: hidden;

    & h6 {
        color: white;
        margin-top: 10px;
    }

    & ul.list-unstyled {
        list-style: none;

        & a {
            text-decoration: none;
            color: var(--footer-menu-text);
            font-size: 10px;
        }
    }

    & .image {
        position: relative;

        & img {
            width: 30rem;
            position: absolute;
            top: -5rem;
            left: 15rem;
        }
    }
}
</style>