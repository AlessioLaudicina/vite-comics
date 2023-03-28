<script>
export default {

    name: "ComicCard",
    props: {
        card: Object,
    }
};
</script>

<template>
    <div class="card">
        <img :src="card.thumb" alt="card.series">
        <h4>{{ card.series }}</h4>

    </div>
</template>

<style>
.card {
    position: relative;
    width: calc(100% / 6);
    padding: 20px;

}

img {
    width: 150px;
    height: 150px;
    cursor: pointer;
}

h4 {
    color: white;
    font-size: 0.85rem;
    padding: 5px 0;
    vertical-align: middle;

}

p {
    text-align: center;
    position: absolute;
    top: 30%;
    left: 25%;
    opacity: 0;
    transition: 0.8s all;
    color: white;

    font-weight: 600;
    font-size: 0.9rem;
}
</style>