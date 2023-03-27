<script>
export default {

    name: "TheHeader"
}

</script>

<template>
    <header class="content">

        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="Logo DC">
        </div>

        <nav>
            <ul>
                <li> <a>Characters</a> </li>
                <li> <a>Comics</a> </li>
                <li> <a>Movies</a> </li>
                <li> <a>TV</a> </li>
                <li> <a>Games</a> </li>
                <li> <a>Collections</a> </li>
                <li> <a>Videos</a> </li>
                <li> <a>Fans</a> </li>
                <li> <a>News</a> </li>
                <li> <a>Shop</a> </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
header {
    line-height: 120px;
    display: flex;
    justify-content: space-between;
    margin: auto;
}

.logo {
    display: flex;
    align-items: center;
}

img {
    height: 90px;
    cursor: pointer;
}


ul {
    height: 100%;
    list-style-type: none;
    margin: 0 auto;
    display: flex;
}

li {
    margin: 0 10px 0 10px;
    display: flex;
}

a {
    text-decoration: none;
    color: black;

}
</style>