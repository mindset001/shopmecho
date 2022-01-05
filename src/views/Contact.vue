<template>
  <div>
      <div>
          <Navbar/>
    <div class="hero">
    <h1>Contact Us</h1>
    
    </div>
      </div>

      <one/>
  </div>
</template>


<script>
import Navbar from '@/components/Navbar.vue'
// import Product from '@/components/Product.vue';
import One from '@/components/One.vue'


export default {
    components:{
        Navbar,
        // Product,
        One,
       
    }
    
}
</script>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Licorice&display=swap');

  .hero{
    background: black;
    display: flex;
    height: 300px;
    color: #dfb871;
    justify-content: center;
    align-items: center;
    
  }
</style>
