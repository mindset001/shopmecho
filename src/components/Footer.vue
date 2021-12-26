<template>
    <div>
        <div class="general">
            <div class="left">
            <h1>Get the ShopMecho App</h1>
            <p>Enjoy 360 degree automotive solutions at <br> your
             fingertips and get the best out of your car</p>
            <a href="" class="mobile">
                 <img src="../assets/google-play.png" alt="" >
            </a>
        </div>

         <div class="right">
         <img src="../assets/iphone-x.webp" alt="">
         <img src="../assets/pixel-4.png" alt="" class="second">
         </div>
        </div>
        <div class="footer">
            <div>
            <p style="paddint-top:10px;">© 2021 ShopMecho Nigeria Ltd. All rights reserved.</p>
            </div>
            <div class="nav">
                 <ul>
                <li>Home</li>    
                <li>About</li> 
                <li>Services</li>
                <li>Shop</li>     
                
            </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .general{
        padding-top: 6em;
        padding-left: 20em;
        padding-right: 20em;
        display: flex;
        justify-content: space-between;
    }
    .left p{
        margin-top: 60px;
        margin-bottom: 60px;
        font-size: 20px;
        font-family: Arial, Helvetica, sans-serif;
    }
    .left h1{
        font-size: 32px;
    }
    .right img{
        width: 400px;
        height: 400px;
    }
    .second{
        margin-left: -200px;
    }
    .footer{
        background: #0a1133;
        height: 80px;
        display: flex;
        color: #fff;
        justify-content: space-between;
        padding-left: 10em;
        padding-right: 10em;
    }

    nav{
        display: flex;
        justify-content: space-between;
        padding-left: 20px;
        padding-right: 20px;
       
    }
    ul{
     display: flex; 
        list-style-type: none;
        padding-top: 10px;
        padding-right: 40px;
    }
    li{
        margin-right: 40px;
    }

@media screen and (max-width: 480px) {
     .general{
        padding-top: 6em;
        margin-left: -18em;
        display: flex;
        flex-direction: column;
    }
    .right img{
        width: 300px;
        height: 300px;
    }
    .second{
        margin-left: -200px;
        display: none;
    }
      .left p{
        margin-top: 60px;
        margin-bottom: 60px;
        font-size: 20px;
        font-family: Arial, Helvetica, sans-serif;
         width: 350px;
    }
    .left h1{
        font-size: 32px;
        width: 400px;
    }
    .mobile{
        width:50px;
    }
    .nav{
        display: none;
    }
    .footer{
        background: #0a1133;
        height: 80px;
        display: flex;
        color: #fff;
        justify-content: space-between;
        padding-left: 1em;
        padding-top: 20px;
    }
   
}
</style>
