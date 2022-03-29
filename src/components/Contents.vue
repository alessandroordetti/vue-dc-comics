<template>
    <div class="contents-wrapper">
        <div class="contents">

        </div>

        <div class="blue-section">
            <div v-for="(element, index) in mainContents" :key=index>
                <img :src="require(`@/assets/img/${element.image}`)" :alt="element.text">

                <h3>{{element.text}}</h3>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexContents',
    data: function() {
        return {
            mainContents: [
                {
                    image: 'buy-comics-digital-comics.png',
                    text: 'Digital Comics',
                },
                {
                    image: 'buy-comics-shop-locator.png',
                    text: 'DC Merchandise',
                },
                {
                    image: 'buy-comics-subscriptions.png',
                    text: 'Subscriptions',
                },
                {
                    image: 'buy-comics-merchandise.png',
                    text: 'DC Power Visa',
                },
                {
                    image: 'buy-dc-power-visa.svg',
                    text: 'Digital Comics',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .contents-wrapper {
        background-color: #0282f9;

        img {
            height: 50%;
            margin-right: 1.5rem;
        }
    }



    .blue-section {
        width: 65%;
        margin: 0 auto;
        display: flex;

        & div {
            color: white;
            display: flex;
            align-items: center;
            padding: 1.5rem;
        }
    }
</style>