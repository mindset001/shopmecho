<template>
    <div class="cover">
        <div class="general">
        <div class="button">
            <a>CONNECT WITH US</a>
        </div>
        <div class="product">
        <img src="../assets/icon-1.png" alt="">
        <img src="../assets/client-01.png" alt="">
        <img src="../assets/client-03.png" alt="">
        <img src="../assets/client-04.png" alt="">
        </div>
    </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style scoped>
.general{
    margin-top: 40px;
    
    
}
.button{
    text-align: center;
    border: none;
    outline: none;
    background: none;
    height: 5em;
    justify-content: center;
    align-items: center;
    padding-top: 40px;
    font-size: 40px;
}
.button a{
    cursor:help;
}

.product{
    background-color: antiquewhite;
    height: 15em;
    display: flex;
    justify-content: space-between;
    padding-left: 20em;
    padding-right: 20em;
    padding-top: 40px;
    padding-bottom: 40px;
}
.product img{
    width: 200px;
    
}
@media screen and (max-width: 480px) {
   
   .product{
    background-color: antiquewhite;
    height: 75em;
    display: flex;
    flex-direction: column;
    padding-top: 40px;
    padding-bottom: 40px;
    margin-left: -14em;
}
.product img{
    width: 200px;
    margin-bottom: 20px;
    
}
.button{
    text-align: center;
    border: none;
    outline: none;
    background: none;
    height: 5em;
    justify-content: center;
    align-items: center;
    padding-top: 40px;
    font-size: 20px;
}
}

</style>
