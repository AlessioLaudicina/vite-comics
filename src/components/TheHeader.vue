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
                <li> <a>CHARACTERS</a> </li>
                <li> <a>COMICS</a> </li>
                <li> <a>MOVIES</a> </li>
                <li> <a>TV</a> </li>
                <li> <a>GAMES</a> </li>
                <li> <a>COLLECTTIONS</a> </li>
                <li> <a>VIDEOS</a> </li>
                <li> <a>FANS</a> </li>
                <li> <a>NEWS</a> </li>
                <li> <a>SHOP</a> </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
header {
    line-height: 120px;
    display: flex;
    justify-content: space-between;

}

.logo {
    display: flex;
    align-items: center;
    margin-left: 30px;
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
    cursor: pointer;
}

a {
    text-decoration: none;
    color: black;

}
</style>