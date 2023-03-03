<template>
    <main class="back-main">
       


     
         <div class="items-card">
            <img class="img_card" :src="thumb" alt="">
            <h1 class="movie_card_title" >{{ series }}</h1> 
         </div>
         <div></div>
           

   

     

    </main>
</template>


<script>
   export default{
      props: {
       
         series: {
            type: String,
            required: true
         },    
         thumb: {
            type: Array ,
            required: true
         }

  }

   }
</script>






<style lang="scss" scoped>


 
 
.back-main{
   flex-basis: calc(100% / 6);

     .items-card{
      padding: 40px 0;;
     }
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


</style>