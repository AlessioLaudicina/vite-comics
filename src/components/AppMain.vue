<script>
import ComicCard from './ComicCard.vue';

export default {
    name: 'AppMain',
    components: {
        ComicCard,
    },
    data() {
        return {
            cards: [
                {
                    "thumb": "https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/BA_Cv9_00911_DIGITAL.jpg?w=640",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/ST_GH_Cv3_00311_DIGITAL.jpg?w=640",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/MS30A_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/MS30A_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/BMSMWF_Cv13_01311_DIGITAL.jpg?w=640",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/NTW_Cv102_10211_DIGITAL-1.jpg?w=640",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/FLS_Cv795_79511_DIGITAL.jpg?w=640",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/DCConnect_35-CVR.jpg?w=640",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/ROBIN_v3%20%28Cover%29.jpg?w=640",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/LP-ROTG_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/SM_LOST_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }
};
</script>

<template>
    <main>
        <div class="jumbotron">
            <img src="../assets/img/jumbotron.jpg" alt="jumbotron" />
        </div>
        <h2 class>Current series</h2>
        <div class="content">

            <ComicCard v-for="(card, index) in cards" :key="index" :card="card" />

        </div>
        <button>LOAD MORE</button>
    </main>
</template>

<style>
main {
    padding-bottom: 30px;
    background-color: #1d1c1c;
    color: white;
}

h2 {
    width: 215px;
    transform: translateY(-50%);
    margin-left: 6%;
    text-align: center;
    color: white;
    padding: 8px;
    background-color: #0082f9;
    border: 1px solid;
    cursor: pointer;
}

.jumbotron {
    height: 400px;
}

.jumbotron img {
    height: 100%;
    width: 100%;

}

.content {
    display: flex;
    flex-wrap: wrap;
    margin: 0 50px;
}

button {
    margin: 5px auto;
    display: block;
    color: white;
    font-weight: bold;
    background-color: #0082f9;
    cursor: pointer;
    padding: 5px;
    width: 150px;
    border: none;
}
</style>