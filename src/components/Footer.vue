<template>
    <div class="background">

        <div class="contacts-wrapper">
            <div class="contacts-1">
                <h3>
                    DC COMICS
                </h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>

                <h3></h3>

                <h3>SHOP</h3>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div class="contacts-2">
                <h3>DC</h3>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (new)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshop</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>

            <div class="contacts-3">
                <h3>
                    Sites
                </h3>

                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>Dc Kids</li>
                    <li>Dc Universe</li>
                    <li>Dc Power Visa</li>
                </ul>
            </div>

            <div class="dc-bigger-logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>

        <div class="footer-wrapper">
            <div class="social-media-contacts">
                <button>Sign-up now!</button>

                <div>
                    <span>
                        Follow Us
                    </span>

                    <a href="#"><img src="../assets/img/footer-youtube.png" alt="Logo Youtube"></a>
                    <a href="#"><img src="../assets/img/footer-facebook.png" alt="Logo Facebook"></a>
                    <a href="#"><img src="../assets/img/footer-twitter.png" alt="Logo Twitter"></a>
                    <a href="#"><img src="../assets/img/footer-pinterest.png" alt="Logo Pinterest"></a>
                    <a href="#"><img src="../assets/img/footer-periscope.png" alt="Logo Pinterest"></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexFooter',
}
</script>

<style lang="scss" scoped>
    h3 {
        margin: 0;
    }

    ul {
        list-style-type: none;
        padding: 0;
        list-style-type: none;

        & li {
            margin-bottom: .4rem;
        }
    }
    
    .background {
        background-color: #303030e1;
    }

    .contacts-wrapper {
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        height: 480px;
        color: white;
        display: flex;
        justify-content: space-evenly;
        padding-top: 1rem;
    }

    .dc-bigger-logo img{
        width: 90%;
    }
    
    .footer-wrapper {
        width: 70%;
        margin: 0 auto;

        & .contacts {
            background-image: url('../assets/img/footer-bg.jpg');
            width: 40%;
        }

        & .social-media-contacts {
            display: flex;
            justify-content: space-between;
            align-items: center;

            & div {
                display: flex;
                align-items: center;
                padding: 1.5rem 0;
            }
        }

        & button {
            padding: 1rem;
            border: 3px solid #1067b8;
            background-color: #303030e1;
            color: white;
            text-transform: uppercase;
        }
    }

    div a, div span {
        padding: .5rem;
        font-size: 1.5rem;
        color: #0412d3;
        font-weight: bold;
    }
</style>