<template>
  <div id="nav">
  <nav class="navbar navbar-expand-lg navbar-light mine">
    <a class="navbar-brand" href="#">
        <img src="../assets/long2.png" alt="" style="height:60px; width:80px;">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <div class="navbar-nav mr-auto">
            <router-link to="/" class="nav-item nav-link">Home</router-link>
            <router-link to="/about" class="nav-item nav-link">About</router-link>
            <router-link to="/services" class="nav-link">Services</router-link>
            <router-link to="/contact" class="nav-link">Contact</router-link>
        </div>
        
    </div>
</nav>
 <router-view/>
 </div>
 
</template>



<style scoped>
    
   
    .mine{
    display: flex;
    justify-content: space-between;
    background: transparent;
    color: aliceblue;

    }
    #nav a {
    font-weight: bold;
    color: blueviolet;
    }

    #nav a.router-link-exact-active {
    color: black;
    background: yellowgreen;
    border-radius: .5rem;
}
</style>
