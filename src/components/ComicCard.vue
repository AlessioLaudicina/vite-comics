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
        <p>
            {{ card.price }} <br />
            buy!
        </p>
    </div>
</template>

<style></style>