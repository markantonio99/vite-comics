
<template>
    <footer>
        <div class="backgrounf-footer">
            <img class="back_tumb_foot" src="/public/dc-logo-bg.png" alt="">
            <div class="footer_head">
                  <div class="icon_items">
                    <img src="/public/buy-comics-digital-comics.png" alt="">
                  </div>
                  <div class="icon_items">
                    <img src="/public/buy-comics-merchandise.png" alt="">
                  </div>
                  <div class="icon_items">
                    <img src="/public/buy-comics-shop-locator.png" alt="">
                  </div>
                  <div class="icon_items">
                    <img src="/public/buy-comics-subscriptions.png" alt="">
                  </div>
                  <div class="icon_items">
                    <img src="public/buy-dc-power-visa.svg" alt="">
                  </div>
            </div>

       
          <div class="main-footer">


           <div class="col">
            <h2 class="title_footer">Dc Comics</h2>
            <ul class="body_footer">
                <li>Characters</li>
                <li>Comics</li>
                <li>Mpovies</li>
                <li>Tv</li>
                <li>Game</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <h2 class="title_footer">SHOP</h2>
            <ul class="body_footer">
                <li>Shop Dc</li>
                <li>Shop Dc Celebrites</li>
            </ul>
           </div>


           <div class="col">
            <h2 class="title_footer">DC</h2>
            <ul class="body_footer">
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
            </ul>

           </div>


           <div class="col">
            <h2 class="title_footer">SITES</h2>
            <ul class="body_footer">
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
                <li>Lorem ipsum</li>
            </ul>
           </div>


           </div>

           <div class="dawn-footer">
                 <div class="item_ffot_down">
                    <button class="foot_btn">SIGN UP NOW</button>
                 </div>           
                 <div class="item_ffot_down">
                   
                    <div class="ite_icon_down_foot">
                        <h2 class="follow_footer">FOLLOW US</h2>
                        <div class="foot_icon_down">
                             <img src="/public/footer-facebook.png" alt="">
                            </div>
                            <div class="foot_icon_down">
                             <img src="/public/footer-twitter.png" alt="">
                            </div>
                            <div class="foot_icon_down">
                             <img src="/public/footer-youtube.png" alt="">
                            </div>
                            <div class="foot_icon_down">
                             <img src="/public/footer-pinterest.png" alt="">
                            </div>
                            <div class="foot_icon_down">
                             <img src="/public/footer-periscope.png" alt="">
                            </div>
                    </div>               
                 </div>
           </div>

        </div>
    </footer>
</template>


<script>
   export default{


   }
</script>






<style lang="scss" scoped>

li{
    list-style: none;
}
.footer_head{
    margin-top: -40px;
    display: flex;
    justify-content: center;
    gap: 80px;
    background-color: #0082F9;
    
     

       .icon_items{
        padding: 50px;
       }
}

.backgrounf-footer{
           background-image: url('/public/footer-bg.jpg');
           min-height: 400px;  
           .body_footer{
            color: white;
            padding: 0;
            position: relative;
           }

    

           .title_footer{
            color: white;
            font-size: 30px;
            text-transform: uppercase;
           }
       } 

       .main-footer{
        display: flex;
        gap: 50px;
        margin-left: 80px;
       }
      
  .dawn-footer{
    
    background-color: #303030;
    min-height: 100px;
    display: flex;  
    align-items: center; 
    position: relative;
    z-index: 11;
   

        .item_ffot_down{

            flex-basis: 50%;
            margin: 0 50px;
        }

        .ite_icon_down_foot{
            display: flex;
            gap: 20px;
            justify-content: flex-end;
        }
        .foot_btn{
            background-color: transparent;
            border: 1px solid #0082F9;
            color: white;
            padding: 15px 20px;
            font-weight: 700;
        }
        .follow_footer{
            color: #2058CC;
            margin-top: 5px;
            margin-right: 20px;
        }

  }       
  .back_tumb_foot{ 
         width: 30%;
         position: absolute;
         right:50px;
         top: 75%;
         
        }
</style>