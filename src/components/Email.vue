<template>
    <div style="display:flex; justify-content: space-between;">
      <h1>Email App</h1>

      <ul>
        <li v-for="email in emails" :key="email" @click="detailMail=email">
          <p>{{ email.subject}}  </p>
        </li>
      </ul>
      <email-details :email="detailMail" ></email-details>
    </div>
</template>



<script>
import EmailDetails  from "@/components/EmailDetails.vue";
export default {
    components:{
      EmailDetails
    },
    data(){
       return{
         detailMail: null,
         emails:  [
            {
                id:1,
                subject: 'Send PPT',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                img: 'url("../assets/about-us.jpg")'
            },
            {
                id:2,
                subject: 'Movie Ticket',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                 img: 'url("../assets/about-us.jpg")'
            },
            {
                id:3,
                subject: 'Enroll at Demlinks',
                message: 'Rogers are blown out of their trajectory into an orbit which',
                 img: 'url("../assets/about-us.jpg")'
            },
        ]
       }
    }
}
</script>
