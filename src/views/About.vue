<template>
  <div class="all">
   
  <div>
  <Navbar/>
    <div class="hero">
    <h1>About Our Company</h1>
    
    </div>
    <div class="second">
        <h4 style="color:#dfb871;">All About Us</h4>    
        <h2 style="color:#000;">  WHO WE ARE</h2>
        <p>
            We are a group of technology enthusiasts who are really passionate about making financial inclusion count
        </p>

    </div>

          <div class="third">
            <div class="right">
            <div class="mission">
            <h1>Our Mission</h1>
              Everyday, we strive to understand our customers and leverage technoloy, data and innovation to deliver outstanding service experiences.
            
            </div>
            <div class="vision">
            <h1>Our Vision</h1>
            <p>We are Nigeria's most convenient company delivering outstanding service experience</p>
            
            </div>
            
            </div>

            <div class="left">
            <img src="../assets/about-us.jpg" alt="">
            </div>
          </div>

          <div class="fourth">
          <img src="../assets/experience.png" alt="">
          <div class="text">
            <h1>25 Years of Experience</h1>
            <h2>in Car Maintenance Business</h2>
            <p>Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic
             life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar..</p>
          </div>

          
          </div>
          <div class="fifth">
          <h4 style="color:#dfb871;">Our Awesome Features</h4>    
        <h2 style="color:#000;">  WHY CHOOSE US</h2>
        <div class="cover">

          <div class="one">
            <div>
            <h1>ALWAYS AVAILABLE</h1>
              <p>all mechanicion sites open for visitors, with 24/7 video surveillance being conducted at all objects</p>
            </div>
            <div>
            <h1>FAIR PRICES</h1>
              <p>you can be 100% sure that it will be delivered right on time, within the set budget limits</p>
            </div>
          </div>
          <div class="two">
              <img src="../assets/choose.jpg" alt="">
          </div>
          <div class="three">
            <div>
            <h1>EXPERIENCE MECHANICS</h1>
              <p>We have a team of specialists capable of maximizing the result and delivering the projects</p>
            </div>
            <div>
            <h1>BEST OFFERS</h1>
              <p>All aspects of the operations being transparent and clear for clients and partners</p>
            </div>
          </div>
        
        </div>
          
          </div>
          
          <div class="sixth">
              <h4 style="color:#dfb871;">Our Creative Teams</h4>    
              <h2 style="color:#000;">    TEAM MEMBERS</h2>
              <p>
                  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur
                  . Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>

              <div class="inner">
              <div>
                <img src="../assets/slide2-img.png" alt="">
                <h4>DOUGLAS GILBERT</h4>
                <h6>Supervisor</h6>
              </div>
              <div>
                <img src="../assets/slide2-img.png" alt="">
                <h4>DOUGLAS GILBERT</h4>
                <h6>Supervisor</h6>
              </div>
              <div>
                <img src="../assets/slide2-img.png" alt="">
                <h4>DOUGLAS GILBERT</h4>
                <h6>Supervisor</h6>
              </div>
              <div>
                <img src="../assets/slide2-img.png" alt="">
                <h4>DOUGLAS GILBERT</h4>
                <h6>Supervisor</h6>
              </div>
              
              </div>

          </div>
  </div>
  
   <!-- <Product/> -->
    <Footer/>

  </div>
</template>


<script>
import Navbar from '@/components/Navbar.vue'
// import Product from '@/components/Product.vue';
import Footer from '@/components/Footer.vue'


export default {
    components:{
        Navbar,
        // Product,
        Footer,
       
    }
    
}
</script>

<style scoped>

  .hero{
    background: black;
    display: flex;
    height: 300px;
    color: #dfb871;
    justify-content: center;
    align-items: center;
    
  }
  .second{
    display: flex;
    flex-direction: column;
    height: 300px;
    justify-content: center;
    align-items: center;
  }
  .third{
    display: flex;
    padding-left: 20em;
    padding-right: 20em;
  }
   .fourth{
    display: flex;
    padding-left: 20em;
    padding-right: 20em;
    background: #dfb871;
  }
  .mission{
    text-align: center;
  }
  .vision{
  padding-top: 40px;
    text-align: center;
  }
  .text{
    color: #fff;
    padding-top: 80px;
  }
  .cover{
    display: flex;
    padding-left: 20em;
    padding-right: 20em;  
    padding-top: 60px;
    align-items:left;
  }
  .one{
    padding-top: 3em;
    text-align: right; 
    padding-right: 3em; 
  }
  .three{
    padding-top: 3em;
    padding-left: 3em;
  }
  .one h1{
    justify-content: left;
    font-size: 24px;
  }
.three h1{
    text-align: left;
    justify-content: left;
    font-size: 24px;
  }

  .fifth{
    display: flex;
    flex-direction: column;
    padding-top: 80px;
    justify-content: center;
    align-items: center;
  }
  .sixth{
    background: #f9f9f9;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
    padding-top: 5em;
    padding-block-end: 5em;
  }
  .sixth p{
    text-align: center;
    width: 60em;
  }
  .inner{
    display: flex;
    justify-content: space-between;
    margin-top: 5em;
  }
  .inner img{
    width: 15em;
    height:20em;
    margin-right: 50px;
    border-bottom: solid 1px #dfb871;
  }
  .inner h4{
    padding-top: 30px;
    text-align: center;
    font-size: 16px;
    margin-right: 50px;
  }
  .inner h6{
    text-align: center;
    margin-right: 50px;
    font-size: 10px;
  }


  @media screen and (max-width: 480px) {

  .all{
    overflow: hidden;
  }
     .second{
      width: 400px;
      padding-left: 20px;
      padding-right: 10px;
      text-align: center;
     }

     .left{
      display: none;
     }

     .third{
      display: flex;
      flex-direction: column;
      padding-left: 10px;
      width: 400px;
     }
     .mission{
      width: 400px;
      text-align: center;
      padding-left: 10px;
      padding-right: 10px;
     }
      .vision{
      padding-top: 40px;
      width: 400px;
      text-align: center;
      padding-left: 10px;
      padding-right: 10px;
     }

     .fourth{
       display: flex;
      flex-direction: column;
      padding-left: 10px;
     }
     .fourth img{
        width: 400px;   
       }

       .text{
          width: 400px;
          text-align: center;
       }
       .cover{
        display: flex;
        padding-left: 2em;
        padding-right: 2em;  
        padding-top: 60px;
        align-items:left;
        justify-content: center;
  }
       .two{
        display: none;
       }
       .one h1{
    justify-content: left;
    font-size: 16px;
  }
.three h1{
    text-align: left;
    justify-content: left;
    font-size: 16px;
  }
   .one{
    padding-top: 3em;
    text-align: right; 
    padding-right: 1em; 
  }
  .three{
    padding-top: 3em;
    padding-left: 1em;
  }

  .inner{
    display: flex;
    flex-direction: column;
  }

  .sixth{
    background: #f9f9f9;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 5em;
    padding-block-end: 5em;
  }
  .sixth p{
    text-align: center;
    width: 20em;
  }
   
}
</style>

