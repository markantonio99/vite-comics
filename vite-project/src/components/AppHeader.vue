<template>

       <div class="head-flex">
            <div class="head_tumb"> <img src="/public/dc-logo.png" alt=""></div>
            <div class="head_list_nav"> 
                <ul class="flex_nav">
                    <li class="munu_items">Characters</li>
                    <li class="munu_items active">Comics</li>
                    <li class="munu_items">Movies</li>
                    <li class="munu_items">Tv</li>
                    <li class="munu_items">Games</li> 
                    <li class="munu_items">Collectibles</li>
                    <li class="munu_items">Video</li>
                    <li class="munu_items">Fans</li>
                    <li class="munu_items">News</li>
                    <li class="munu_items">Shop</li>
                </ul>
            </div>
       </div>
</template>

<script>
    export default{

    }
</script>



<style lang="scss" scoped>

.head-flex{
    display: flex;

}
.head_tumb{
    flex-basis: 27%;
    padding: 10px;
}

.head_list_nav{
    flex-basis: 75%;
  
}

.flex_nav{
    display: flex;
    gap: 20px;
    line-height: 100px;
    justify-content:end;
   
}

.munu_items{
    font-weight: 700;
    font-size: 15px;

}

li{
    list-style: none;
    text-transform: uppercase;
}

.active{
    color: blue;
}





// .container{
//     display: flex;
//     width: 100%;
// }
// .hed-flex{
   
//     margin: auto;
// }


// .main-menu{
//     display: flex;
  
// }

 
</style>