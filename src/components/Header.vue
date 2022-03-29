<template>
    <div class="header-wrapper">
        <div class="img-wrapper">
            <img src="../assets/img/dc-logo.png" alt="Logo DC">
        </div>

        <nav>
            <ul>
                <li v-for="(element, index) in navList" :key="index">
                    <a :href="element.url">
                        {{element.text}}
                    </a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'IndexHeader',
    data: function () {
        return {
            navList: [
                {
                    text: 'Characters',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Comics',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Movies',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'TV',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Games',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Collectibles',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Videos',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Fans',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'News',
                    active: false,
                    url: '#',
                },
                                {
                    text: 'Shop',
                    active: false,
                    url: '#',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .header-wrapper {
        width: 70%;
        margin: 0 auto;
        margin-bottom: 100px;
        display: flex;
        justify-content: space-between;

        & .img-wrapper img {
            width: 75%;
        }
    }
    
    nav {
        display: flex;
        justify-content: space-evenly;

        & ul {
        display: flex;
        align-items: center;

        & li {
            list-style: none;
            padding: .6rem;
        }

        & a{
            text-transform: uppercase;
            font-weight: bold;
            color: black;
            text-decoration: none;
        }
        }
    }
</style>