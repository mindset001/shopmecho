<template>
    <div class="header">
        <nav>
        <div>
        <img src="../assets/pp.jpeg" alt="">
        </div>
            <div>
                <ul>
                <li><router-link to="/" class="nav-item nav-link">Home</router-link></li>    
                <li><router-link to="/about" class="nav-item nav-link">About</router-link></li> 
                <li><router-link to="/services" class="nav-link">Services</router-link></li>
                
                <li class="btn">
                    Login
                </li>
            </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.header{
       
        background-color: #eee;
        color: #0077b6;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif ;
}

    nav{
        display: flex;
        justify-content: space-between;
        padding-left: 20px;
        padding-right: 20px;
       
    }
    ul{
     display: flex; 
        list-style-type: none;
        padding-top: 10px;
        padding-right: 40px;
    }
    li{
        margin-right: 40px;
    }
    img{
        height: 40px;
        width: 40px;
        border-radius: 50px;
        padding-left: 20px;
        padding: 10px;
    }
         .btn{
        outline: none;
        border: none;
        border: solid 1px #0077b6;
        color: #000;
        padding-left: 10px;
        padding-right: 10px;
        border-radius: 5px;
    }

</style>
