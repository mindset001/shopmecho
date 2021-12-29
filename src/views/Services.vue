<template>
  <div  class="all">
  <Navbar/>
  <div class="hero">
    <h1> Our Services</h1>
    
    </div>
    <div class="second">
        <h4 style="color:#dfb871;">know About Our Services</h4>    
        <h2 style="color:#000;">  WHAT WE DO</h2>
        <p>
            We are a group of technology enthusiasts who are really passionate about making financial inclusion count
        </p>

    </div>
    <div class="third">
    <div class="cover">
        <div class="content">
    <div class="figure">01</div>
    <p>Their house is a mart where people come</p>
    </div>
        <h5>Rogers are blown out of their trajectory into an orbit which 
        freezes his life after support systems and returns to him.</h5>
    </div>


   <div class="cover">
        <div class="content">
    <div class="figure">01</div>
    <p>Their house is a mart where people come</p>
    </div>
        <h5>Rogers are blown out of their trajectory into an orbit which 
        freezes his life after support systems and returns to him.</h5>
    </div>
    <div class="cover">
        <div class="content">
    <div class="figure">01</div>
    <p>Their house is a mart where people come</p>
    </div>
        <h5>Rogers are blown out of their trajectory into an orbit which 
        freezes his life after support systems and returns to him.</h5>
    </div>
    <div class="cover">
        <div class="content">
    <div class="figure">01</div>
    <p>Their house is a mart where people come</p>
    </div>
        <h5>Rogers are blown out of their trajectory into an orbit which 
        freezes his life after support systems and returns to him.</h5>
    </div>


    
    </div>

        <div class="mail">
               <div class="right">
               <h1>WHO CAN USE SHOPMECHO</h1>
                <ul class="desktop">
                <li v-for="email in emails" :key="email" @click="detailMail=email">
                    <p>{{ email.subject}}</p>
                </li>
                </ul>
               </div>
               
               
            <email-details :email="detailMail" class="new"></email-details>
        </div>


  
  
                    <div :class="!email.mobile ? 'mobile' :'mobile-show' " v-for="email in emails" :key="email.id" @click="bigi(email.id)">
                    <p class="para">{{email.subject}}</p>
                    <div class="shakur">
                        <h1>{{email.subject}}</h1>
    
                <p>{{email.message}}</p>

                <img :src= "require('@/assets/' + email.image)"  alt=""/>
             </div>
       
               </div>



   <Product/>
    <One/>

  </div>
</template>


<script>
import Navbar from '@/components/Navbar.vue'
import Product from '@/components/Product.vue';
import One from '@/components/One.vue'
import EmailDetails  from "@/components/EmailDetails.vue";

export default {
     
    components:{
        Navbar,
        Product,
    One,
    EmailDetails
    },
    data(){
       return{
           
         detailMail:null,
         emails:  [
            {
                    mobile: false,
                id:1,
                subject: 'car Owners',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:2,
                subject: 'Auto Repair Shop',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:3,
                subject: 'Vehicle Workshop Owners',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "offer-img.jpg"
            },
            {
                id:4,
                subject: 'Auto Service Providers',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:5,
                subject: 'Automobile Mechanics ',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:6,
                subject: 'Automobile Technician',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "offer-img.jpg"
            },
        
        {
            mobile: false,
                id:7,
                subject: 'Automobile Parts sellers',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:8,
                subject: 'Automobile Washing Centres',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:9,
                subject: 'Vehicle Tyre Workshops ',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "offer-img.jpg"
            },
            {
                mobile: false,
                id:10,
                subject: 'Body work specialists',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:11,
                subject: 'Auto Ac conditioning ',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "about-us.jpg"
            },
            {
                mobile: false,
                id:12,
                subject: 'Toll service providers ',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "offer-img.jpg"
            },
             {
                 mobile: false,
                id:13,
                subject: 'Logistics services provider ',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                image: "offer-img.jpg"
            },
        
        
        ]
       }
       
    },
    mounted(){
           this.detailMail=this.emails[0]
       },
       methods:{
           bigi(id){
              const dataIndex = this.emails.findIndex(doc => doc.id==id)
              this.emails[dataIndex].mobile = !this.emails[dataIndex].mobile
              console.log(dataIndex)
       } 
    
}
}
</script>

<style scoped>
.mobile{
    display: none;
}

.right{
    background: url('../assets/offer-img.jpg');
    width:50%;
    height: 70vh;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    background-size: cover;
    color: #fff;
}
.right h1{
    background: #dfb871;
    padding: 20px;
}
    li{
        background: #dfb871;
        padding-left: 2px;
        font-size: 16px;
    }
.mail{
     margin-top: 3em;
    display: flex;
    background-color: #dfb871;
}
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
      justify-content: space-around;
      padding-left: 20em;
      padding-right: 20em; 
  }
  .cover{

         margin-right: 20px;
  }
  .cover h5{
      font-size: 14px;
      font-weight: 200;
      padding-left: 20px;
      padding-top: 10px;
  }
  .content{
      display: flex;
      align-items: center;
      justify-content: center;
  }
  .content p{
      width: 200px;
  }
   .figure{
         width: 70px;
         height: 70px;
         border-radius: 50%;
         border: solid 5px rgb(219, 215, 215);
         display: flex;
         justify-content: center;
         align-items: center;

         margin-right: 20px;
     }







  @media screen and (max-width: 480px) {

     
      .desktop{
          display: none;
      }
     .second{
      width: 400px;
      padding-left: 20px;
      padding-right: 10px;
      text-align: center;
     }

   
  .third{
      display: flex;
      justify-content: space-around;
      flex-direction: column;
      padding-right: 20em; 
      margin-left: -300px;
      width: 70em;
      margin-bottom: -200px;
  }
  .cover{

         margin-right: 20px;
         margin-left: 20px;
         margin-bottom: 0px;
  }
  .cover h5{
      font-size: 14px;
      font-weight: 200;
      padding-left: 20px;
      padding-top: 10px;
  }
  .content{
      display: flex;
      align-items: center;
      justify-content: center;
  }
  .content p{
      width: 200px;
  }
   .figure{
         width: 70px;
         height: 70px;
         border-radius: 50%;
         border: solid 5px rgb(219, 215, 215);
         display: flex;
         justify-content: center;
         align-items: center;

         margin-left: -120px;
     }
       .cover h5{
      font-size: 14px;
      font-weight: 200;
      padding-left: 20px;
      padding-top: 10px;
      width: 320px;
      margin-bottom: 40px;
  }
  .mail{
     margin-top: 13em;
    display: flex;
    flex-direction: column;
    background-color: #dfb871;
    justify-content: center;
}
.new{
    margin-top: 5em;
    margin-left: -100px;
    width: 500px;
}
ul{
    display: flex;
    justify-content: space-around;
    margin-left: 20em;
}
.right{
    background: url('../assets/offer-img.jpg');
    width:100%;
    height: 40vh;
    display: flex;
    justify-content: center;
    background-size: cover;
    color: #fff;
    padding-left: 10em;
}
li{
    margin-left: 10px;
}
.right h1{
    background-color: #000;
    width: 550px;
    font-size: 24px;
    text-align: center;

}
.new{
    display: none;
}
 .mobile{
     display: block;
          position: relative;
          overflow: hidden;
          height: 8vh;
          transition: all 0.3s ease-in-out;
          
      }
      .mobile-show{
          display: block;
          position: relative;
          overflow: hidden;
          height: 50vh;
          transition: all 0.3s ease-in-out;
      }

      .para{
          background: #dfb871;
          width: 250px;
          margin-bottom: 20px;
          margin-left: 5em;
          margin-top: 1em;
          text-align: center;
      }


   .all{
       overflow: hidden;
   }
}

</style>

