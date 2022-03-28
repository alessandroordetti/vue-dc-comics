<template>
    <div class="header-wrapper">
        <div class="img-wrapper">
            <img src="../assets/img/dc-logo.png" alt="Logo DC">
        </div>

        <nav>
            <ul>
                <li>
                    <a href="#">
                        Characters
                    </a>
                </li>
                <li>
                    <a href="#">
                        Comics
                    </a>
                </li>
                <li>
                    <a href="#">
                        Movies
                    </a> 
                </li>
                <li>
                    <a href="#">
                        TV
                    </a>
                </li>
                <li>
                    <a href="#">
                    Games
                    </a>
                </li>
                <li>
                    <a href="#">
                        Collectibles
                    </a> 
                </li>
                <li>
                    <a href="#">
                        Videos
                    </a>
                </li>
                <li><a href="">
                    Fans
                    </a> 
                </li>
                <li>
                    <a href="#">
                        News
                    </a> 
                </li>
                <li>
                    <a href="#">
                        Shop
                    </a> 
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'IndexHeader',
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
            width: 70%;
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