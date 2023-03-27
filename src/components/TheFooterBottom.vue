<script>
export default {
    name: "TheFooterBottom"

}

</script>

<template>
    <footer>
        <div class="content">
            <button>
                <h4>Sign-up now!</h4>
            </button>
            <div class="follow-us">

                <h4>Follow us</h4>

                <img src="../assets/img/footer-facebook.png" alt="facebook" />
                <img src="../assets/img/footer-twitter.png" alt="twitter" />
                <img src="../assets/img/footer-youtube.png" alt="youtube" />
                <img src="../assets/img/footer-pinterest.png" alt="pinterest" />
                <img src="../assets/img/footer-periscope.png" alt="periscope" />
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    height: 110px;
    background-color: rgb(67, 63, 63);
}

.content {
    display: flex;
    justify-content: space-between;
    height: 100%;
}

button {
    border: 1px solid blue;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 50px;
    width: 150px;
    margin-top: 30px;
}

h4 {
    margin-left: 40px;
    padding: 13px;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;


}

.follow-us {
    display: flex;
}

img {
    margin: 0 3px;
    cursor: pointer;
    transform: scale(0.3);
}

.follow-us>h4 {
    color: blue;
    margin-right: 30px;
    padding-top: 5px;
    font-size: 1.1rem;
    font-weight: 600;
    cursor: pointer;
}
</style>