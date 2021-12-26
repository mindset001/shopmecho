<template >
    <div style="overflow:hidden">

        <div class="hero">
        


        <div class="img">
            <img src="../assets/slide2-img.png" alt="">
        </div>
            <div class="text">
            <h1>Welcome to <span>ShopMecho</span></h1>
            <h2>AutoMobile Repair And Sales</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, nulla? Lorem ipsum dolor sit,
             amet consectetur adipisicing elit. Facere, accusamus?</p>
            <button>Join The community</button>
            </div>
        </div>

        
       
       


        
    </div>
</template>

<script>
export default {
    
    
}

</script>

<style scoped>

    .hero{
        display: flex;
        justify-content: space-between;
        padding-top: 10em;
        padding-right: 5%;
        padding-left: 10%;
        background-image: url('../assets/background-2.jpg');
        color:#fff;
        height: 72.5vh;
    }
    span{
        color: #0077b6;
    }
    .text{
        padding-top: 50px;
    }
    h1{
        font-size: 5em;
    }
    h2{
        font-size: 2em;

    }
    p{
        font-size: 1.5em;
        width: 40em;
        padding-bottom: 40px;
    }
    .img{
        padding-top: 15px;
        width: 20px;
    }
    button{
        width: 150px;
        height: 50px;
        background: #0077b6;
        outline: none;
        border: none;
        border-radius: 10px;
        color: #fff;
        font-weight: bold;
    }
   

   @media screen and (max-width: 480px) {
 .hero{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        color:#fff;
        height: 82.5vh;
    }
    .img{
        margin-top: -65px;
        width: 40px;
    }
     .text{
        margin-top: -2000px;
        color: #fff;
    }
    h1{
        font-size: 3em;
        margin-top: -500px;
    }
    h2{
        font-size: 2em;

    }
    span{
        color: red;
    }
    p{
        font-size: 1.5em;
        width: 15em;
        padding-bottom: 40px;
        display: none;
    }
  
    button{
        width: 150px;
        height: 50px;
        background: red;
        outline: none;
        border: none;
        border-radius: 10px;
        color: #fff;
        font-weight: bold;
    }
}
</style>
