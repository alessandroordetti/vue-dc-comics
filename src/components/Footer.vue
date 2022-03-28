<template>
    <div class="background">
        <div class="footer-wrapper">
            <div class="contacts">

            </div>

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
    .background {
        background-color: #303030e1;
        padding: 1.5rem 0;
    }
    
    .footer-wrapper {
        width: 70%;
        margin: 0 auto;

        & .social-media-contacts {
            display: flex;
            justify-content: space-between;
            align-items: center;

            & div {
                display: flex;
                align-items: center;
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