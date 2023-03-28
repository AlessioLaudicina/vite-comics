<script>
export default {
    name: "TheFooterBottom"

}

</script>

<template>
    <footer>
        <div class="content-footer">
            <button>
                <h3>SIGN-UP NOW!</h3>
            </button>
            <div class="follow-us">

                <h4>FOLLOW US</h4>

                <ul class="social">
                    <li> <img src="../assets/img/footer-facebook.png" alt="facebook" /></li>
                    <li> <img src="../assets/img/footer-twitter.png" alt="twitter" /></li>
                    <li> <img src="../assets/img/footer-youtube.png" alt="youtube" /></li>
                    <li> <img src="../assets/img/footer-pinterest.png" alt="pinterest" /> </li>
                    <li> <img src="../assets/img/footer-periscope.png" alt="periscope" /> </li>

                </ul>
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    height: 110px;
    background-color: #2f2f2f;
    margin: 0 auto;
}

.content-footer {
    display: flex;
    justify-content: space-between;
    height: 100%;
    width: 100%;
}

button {
    border: 1px solid #0082f9;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 50px;
    width: 150px;
    margin-top: 30px;
    margin-left: 30PX;
    background-color: #2f2f2f;
    color: white;

}

button:hover {
    background-color: #0082f9;
}

h4 {
    margin-left: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.follow-us {
    display: flex;
    height: 100%;
}

.social {
    display: flex;
    flex-wrap: nowrap;
    padding-right: 85px;
}

.social li {
    list-style: none;
    padding: 0;
    margin: 0;
    width: 70px;
}

img {

    cursor: pointer;
    transform: scale(0.2);
    padding: 0;
    height: 100px;
}

.follow-us>h4 {
    color: #0082f9;
    margin-right: 30px;
    padding-top: 5px;
    font-size: 1.1rem;
    font-weight: 600;
    cursor: pointer;
}
</style>