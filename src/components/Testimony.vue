<template>
    <div>
        <div class="general">
            <div class="left">
        <h1>TESTIMONIAL</h1>
        <p class="para">Lorem ipsum dolor sit amet.</p>


        <div class="image">
            <img src="../assets/Surprise.jpg" alt="" class="img">
            <img src="../assets/Surprise.jpg" alt="" class="img">
            <img src="../assets/Surprise.jpg" alt="" class="img">
            <img src="../assets/Surprise.jpg" alt="" class="img">
            <img src="../assets/Surprise.jpg" alt="" class="img none" >
        </div>


        <div class="line"></div>
        
            

             <!-- testimonials  -->

        <section>
           

            <div class="default-width1">
               <!-- Slideshow container -->
<div class="slideshow-container">

    <!-- Full-width images with number and caption text -->
    <div class="mySlides fade">
        <div class="parent">
           
            <div >
                <div class="upper">
                    <img src="../assets/upperquotation.png" alt="" style="width: 64px;height: 48.7px;">
                    <h3 >They are proficient in designing world class 
                        website to suit your business and i love the 
                        taste and feel of my website..</h3>
                </div>
                <div class="lower">
                    <div>
                        <h4>John Tee</h4>
                        <p>CEO,ChopBeta</p>
                    </div>
                    <div>
                        <img src="../assets/lowerquotation.png" alt="">
                    </div>
                </div>
            </div>
                
        </div>
    </div>

  
  
   
  
    <!-- Next and previous buttons -->
   
  </div>
  <br>
  
  <!-- The dots/circles -->
  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>


                
            </div>
            <div class=" ball">
                <div class="circle"> </div>
                <!-- <div class="circle"></div>
                <div class="circle"></div> -->
            </div>
        </section>
        </div>
       

        <div class="right">
        <h1>GALLERY</h1>
        <div class="image">
            <img src="../assets/Surprise.jpg" alt="" class="gallery">
            <img src="../assets/Surprise.jpg" alt="" class="gallery">
        </div>
         <div class="image">
            <img src="../assets/Surprise.jpg" alt="" class="gallery">
            <img src="../assets/Surprise.jpg" alt="" class="gallery">
        </div>
         <div class="image">
            <img src="../assets/Surprise.jpg" alt="" class="gallery">
            <img src="../assets/Surprise.jpg" alt="" class="gallery">
        </div>
        
        </div >
        </div>
    </div>
</template>






<script>
export default {
    name:'mySlides',
    method:{
        
    }
}
// eslint-disable-next-line no-unused-vars
// import scroll from '../assets/scroll.js';
</script>


<style scoped>
    .general{
        display: flex;
        justify-content: space-between;
        padding-left: 20em;
        padding-right: 20em;
        margin-top: 4em;
        margin-bottom: 4em;
    }
    .image{
        display: flex;
        justify-content: space-between;
    }
    .img{
        border-radius: 50%;
        height: 80px;
        width: 80px;
        box-shadow: 2px 2px #a3d3ec;
        margin-right: 10px;
    }

    .line{
        background: #a3d3ec;
        width: 500px;
        height: 2px;
        margin-top: 40px;
    }
    .gallery{
        height: 14em;
        width: 15em;
    }
    .parent{
    background: #FFFFFF;
    box-shadow: 1px 4px 10px rgba(0, 0, 0, 0.1);
    width: 500px;
    height: 400px;
    position: relative;
    top: 40px;
    margin-bottom: 100px;
    padding-top: 67px;
    display: flex;
    justify-content: center;
}
.upper{
    
    display: flex;
    flex-direction: column;
}

.upper h3{
    font-family: Poppins;
    font-style: normal;
    font-weight: 200;
    font-size: 20px;
    line-height: 30px;
    width: 395px;
}
.lower{
    display: flex;
    flex-direction: row;
    margin-top: 40px;
    justify-content: space-between;
}

.lower h4{
    font-family: Poppins;
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 30px;
    color: #F4743B;
    /* background: linear-gradient(117.01deg, #F2A839 5.4%, #F4743B 99%); */

}
.lower p{
    font-family: Poppins;
    font-style: normal;
    font-weight: 300;
    font-size: 18px;
    line-height: 30px;
}

.ball{
    display: flex;
}
.circle{
    width: 150px;
    height: 15px;
    color: #9B4C0E;
}

@media screen and (max-width: 480px) {
   
   .general{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        margin-left: -18em;
        margin-top: 4em;
        margin-bottom: 4em;
    }
       .parent{
    background: #FFFFFF;
    box-shadow: 1px 4px 10px rgba(0, 0, 0, 0.1);
    width: 350px;
    height: 400px;
    padding-left: 20px;
    
}
    p{
        width: 300px;
    }
    .upper h3{
    font-family: Poppins;
    font-style: normal;
    font-weight: 200;
    font-size: 20px;
    line-height: 30px;
    width: 345px;
}
    .gallery{
    
        height: 8em;
        width: 10em;
    }
    .image{
    display: flex;
    }
    .none{
        display: none;
    }

}


</style>
