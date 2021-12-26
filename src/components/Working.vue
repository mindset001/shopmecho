<template>
    <div >
        <div class="cover">
            <div class="contain">
                    <div class="text">
                <h1>WE ARE WORKING FOR YOU</h1>
                <div class="under">
                    <div class="two">
                        <h2>SPECIALIZED AUTOMOTIVE CARE</h2>
                        <p>
                            Aenean semper nisi ut neque molestie posuere ac id tortor. Nam ut massa tincidunt, volutpat sapien sed, gravida velit.
                        </p>
                    </div>
                    <div class="two">
                         <h2>AAA CERTIFIED CAR REPAIR FACILITY</h2>
                        <p>
                            Aenean semper nisi ut neque molestie posuere ac id tortor. Nam ut massa tincidunt, volutpat sapien sed, gravida velit.
                        </p>
                    </div>
                </div>
                <div>
                <iframe width="420" height="345" src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1&mute=1">
</iframe>
            </div>
            </div>
            
            
                <div class="line"></div>

                <div class="meet">
                    <h1>MEET OUR TEAM</h1>
                    
                    <div class="mobile">
                         <div class="image">
                            <img src="../assets/Surprise.jpg" alt="">
                        <h3>Gregory Evans</h3>
                        <p>OWNER</p>
                        </div>
                        <div class="image">
                            <img src="../assets/Surprise.jpg" alt="">
                        <h3>S.M Ademola</h3>
                        <p>DEVELOPER</p>
                        </div>
                    </div>

                        <div class="mobile">
                            <div class="image">
                            <img src="../assets/Surprise.jpg" alt="">
                        <h3>Gregory Evans</h3>
                        <p>OWNER</p>
                        </div>
                        <div>
                            <img src="../assets/Surprise.jpg" alt="">
                        <h3>S.M Ademola</h3>
                        <p>DEVELOPER</p>
                        </div>
                        </div>

                </div>
            </div>

        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style scoped>
    .cover{
        background:  linear-gradient(
      rgba(104, 102, 102, 0.9), 
      rgba(243, 241, 241, 0.4)
    ), url('../assets/background-3.jpg');
    color: #fff;
    margin-top: 40px;
    background-size: cover;
    padding-top: 40px;
    padding-right: 20em;
    padding-left: 20em;
    padding-bottom: 5em;
       
    }
    .contain{
        padding-top: 20px;
    display: flex;
    }
    
    .under{
        display: flex;      
    
    }
    .text h1{
        text-align: center;
        font-size: 40px;
    }
    img{
        height: 80px;
        width: 80px;
        
    }
    .meet{
        width: 30em;
    }
    h1{
        font-size: 20px;
        margin-bottom: 40px;
    }
    .meet h1{
        padding-top: 20px;
    }


    .line{
        width: 20px;
        height: 10em;
        color: #fff;
    }


    video{
        width: 50em;
        height: 40em;
    }
    .two{
        margin-right: 20px;
    }
    .image{
        margin-bottom: 60px;
    }

@media screen and (max-width: 480px) {
      .contain{
        padding-top: 20px;
        display: flex;
        flex-direction: column;
        }

      .cover{
    padding-top: 40px;
    margin-left: -18em;
    padding-bottom: 5em;
       
    }
    h1{
        width: 350px;
    }
    video{
        width: 20em;
        height: 20em;
    }
    .mobile{
        display: flex;
        justify-content: space-between;
        width: 300px;
    }
   
}
</style>
