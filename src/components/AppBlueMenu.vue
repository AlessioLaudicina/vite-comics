<script>
export default {
    name: "AppBlue"

}

</script>

<template>
    <div class="menu-box">
        <div class="content">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="" />
                    <a href="#">MERCHANDISE</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
                    <a href="#">SHOP</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
                    <a href="#">SUBSCRIPTIONS</a>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
                    <a href="#">VISA</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
.menu-box {
    background-color: #0082f9;

}

ul {
    display: flex;
    justify-content: space-around;
}

li {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 10px;
}

img {
    transform: scale(0.5);
}

a {
    text-decoration: none;
    color: white;
    font-size: 0.9rem;

}
</style>