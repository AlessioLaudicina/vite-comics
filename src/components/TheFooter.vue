<script>
export default {
    name: "TheFooter"

}

</script>

<template>
    <footer>
        <div class="content">
            <div class="cols">
                <div class="links">
                    <h4>DC COMICS</h4>
                    <nav>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </nav>
                </div>
                <div class="links">
                    <h4>SHOP</h4>
                    <nav>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
            <div class="cols">
                <div class="links">
                    <h4>DC</h4>
                    <nav>
                        <ul>
                            <li><a href="#">Terms of use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
            <div class="cols">
                <div class="links">
                    <h4>SITES</h4>
                    <nav>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    display: flex;
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;

}

.content {
    display: flex;
    height: 370px;
    width: 100%;
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: right;
}

.cols {
    padding-top: 30px;
    margin-left: 50px;
}

h4 {
    color: white;

    font-weight: 600;
    margin-bottom: 10px;
}

ul {
    list-style: none;
    padding-bottom: 20px;
}

a {
    display: inline-block;
    text-decoration: none;
    color: gray;
    font-size: .85em;
}
</style>