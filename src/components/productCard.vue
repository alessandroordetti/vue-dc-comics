<template>
    <div class="comics-card">
        <img :src="thumb" :alt="series">
        <h3>{{series}} </h3>
    </div>
</template>

<script>
export default {
    name: 'productCard',
    props: ['thumb', 'price', 'series', 'type']
}
</script>

<style lang="scss" scoped>
                .comics-card {
                    margin-right: 15px;
                    width: calc((100% - 90px) / 6);
                    img {
                        width: 100%;
                        height: 250px;
                    }
                }
</style>