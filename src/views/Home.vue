<template>
  <div class="home">
  <Header />
    <Hero />
    <Services/>
     <Working/>
    <Testimony/>
    <Contact/>
    <Product/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Services from '@/components/Services.vue';
import Working from '@/components/Working.vue';
import Testimony from '@/components/Testimony.vue';
import Contact from '@/components/Contact.vue';
import Product from '@/components/Product.vue';
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Services,
    Working,
    Testimony,
    Contact,
    Product,
    Footer
}
}
</script>
