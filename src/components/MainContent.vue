<template>
    <main class="content">
        <div class="container">
            <ul class="grid">
                <li class="card" v-for="(el, i) in cards" :key="i">
                    <img :src="el.thumb" alt="">
                    <span class="card_series">{{ el.series }}</span>
                </li>
            </ul>            
        </div>
        <div class="load">
            <button class="load-more">load more</button>
        </div>
    </main>
</template>
  
<script>
export default {

    data() {
        return {
            cards: [
                {
                    "thumb": "./img/jimm-lee.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/american-vampire.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/aquaman.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "./img/batgirl.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/batman.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/batman-beyond.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/batman-superman.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/batman-superman-annual.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/batman-joker.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/three-joker.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/harley-queen.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "./img/catwoman.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }

}
</script>
  
<style lang="scss" scoped>
.content {
    background-color: black;
    color: white;
    padding-bottom: 50px;
    text-transform: uppercase;

    .grid {
        display: grid;
        grid-template-columns: repeat(6, 1fr);
        row-gap: 30px;
        

        .card {
            padding: 20px;

            img{
                width: 100%;
                height: 100%;
                aspect-ratio: 1/1;
                object-fit: cover;
            }
        }

    }
}

.card_series {
    font-size: 11px;
}

.load{
    display: flex;
    justify-content: center;
    margin-top: 80px;

    .load-more{
        text-transform: uppercase;
        padding: 8px 25px;
        background-color: rgb(2, 130, 249);
        color: white;
        font-weight: 600;
    }
    
}
</style>