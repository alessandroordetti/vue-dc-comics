<template>
    <div class="contents-wrapper">
        <div class="contents">

        </div>

        <div class="blue-section">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics Logo">

                <h3>Digital Comics</h3>
            </div>

                <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics Logo">

                <h3>Digital Comics</h3>
            </div>

                <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics Logo">

                <h3>Digital Comics</h3>
            </div>

                <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics Logo">

                <h3>Digital Comics</h3>
            </div>

                <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics Logo">

                <h3>Digital Comics</h3>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexContents'
}
</script>

<style lang="scss" scoped>
    .contents-wrapper {
        background-color: #0282f9;
    }

    .blue-section {
        width: 65%;
        margin: 0 auto;
        display: flex;

        & div {
            color: white;
            display: flex;
            align-items: center;
        }
    }
</style>