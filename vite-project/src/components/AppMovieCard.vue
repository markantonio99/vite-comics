<template>
    <main class="back-main">
       


     <div class="flex-card">
        <div v-for="(movie,i) in movies" :key="i" class="movie_items_card">
            <img class="img_card" :src="movie.thumb" alt="">
             <h1 class="movie_card_title" >{{ movie.series }}</h1>             
        </div>
     </div>
           

   

     

    </main>
</template>


<script>
   export default{
      props: {
       
         series: {
            type: String,
            required: true
         },       

  },

   }
</script>






<style lang="scss" scoped>


 
.flex-card{
    background-color:#1C1C1C ;
    display: flex;
    font-size: 5px;
    flex-wrap: wrap;
    padding: 50px 50px;
    .movie_items_card{
         flex-basis: calc(100% / 6);

         } 

         .img_card{
            margin: 0 auto;
            max-width: 150px;
            display: block;
         }
         .movie_card_title{
            text-align: center;
            color: white;
            font-size: 15px;
            font-weight: 500;
         }

         

}


</style>