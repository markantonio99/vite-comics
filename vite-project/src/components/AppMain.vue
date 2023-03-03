
<template>
  <main>
    <div class="content_image">
    </div>
    <div class="content_main">
        <div class="main-movie">      
        <AppMovieCard v-for="(element,vie,i) in movies" :key="i" :series="element.series" :thumb="element.thumb"  />         
     </div>
    </div>
   
   
  </main>
</template>


<script>
import AppMovieCard from './AppMovieCard.vue';
export default{
  components: { 
    AppMovieCard,
},
    data(){
        return {
            movies: [
  {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.cinejosh.com/reviewsimg/big/atm-web-series-review_b_2001231222.jpg",
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
     
      

     
     .content_image{
        background-image: url('/public/jumbotron.jpg');
        padding: 200px 0;
     }

     .content_main{
        background-color: black;
      
     }

     .main-movie{

        display: flex;
        flex-wrap: wrap;
        justify-content: center;
     }
  
</style>

