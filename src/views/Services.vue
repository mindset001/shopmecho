<template>
  <div >
  <Navbar/>
   <Product/>
    <Footer/>

  </div>
</template>


<script>
import Navbar from '@/components/Navbar.vue'
import Product from '@/components/Product.vue';
import Footer from '@/components/Footer.vue'

export default {
    components:{
        Navbar,
        Product,
    Footer
    }
    
}
</script>

<style scoped>

</style>

