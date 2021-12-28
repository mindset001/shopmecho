<template>
    <div class="want" v-if="email">
        <h1>{{email.subject}}</h1>
    
       <p>{{email.message}}</p>

       <img :src= "require('@/assets/' + email.image)"  alt=""/>
        
    </div>
</template>


<script>
export default {
    props:['email']
}
</script>

<style scoped>
.want{
    padding-left: 8em;
}

img{
    width: 30em;
}


@media screen and (max-width: 480px) {
    img{
        width: 22em;
    }
}
</style>
