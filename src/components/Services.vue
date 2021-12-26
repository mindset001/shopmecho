<template>
    <div class="general">
        <div>
            <div>
                <p>We are expert in</p>
            <h1>OUR SERVICES</h1>
            <P class="para">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
            Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</P>
            </div>

            <div>
                <div class="content">
                    <div class="inner">
                    <img src="../assets/icon1.png" alt="">
                    <h2>General Maintenance</h2>
                    <h3>General Maintenance</h3>
                    
                    </div>
                    <div>
                        <div class="inner">
                    <img src="../assets/icon2.png" alt="">
                    <h2>General Maintenance</h2>
                    <h3>General Maintenance</h3>
                    
                    </div>
                    </div>
                </div>


                
                <div>
                    <div class="content">
                    <div class="inner">
                    <img src="../assets/icon3.png" alt="">
                    <h2>General Maintenance</h2>
                    <h3>General Maintenance</h3>
                    
                    </div>
                    <div>
                        <div class="inner">
                    <img src="../assets/icon4.png" alt="">
                    <h2>General Maintenance</h2>
                    <h3>General Maintenance</h3>
                    
                    </div>
                    </div>
                </div>
                </div>
            </div>


        </div>

        <div class="right">
        <div>
            <div class="quest">
        <p>Ask a Question?</p>
        <h1>MAKE ENQUIRY</h1>
        </div>
        <form action="">
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Email">
        <input type="number" placeholder="Telephone">
        <textarea name="" id="" cols="30" rows="10" placeholder="Your Enquiry"></textarea> <br>
        <button type="submit">Submit</button>

        </form>
         <div>
            <img src="../assets/now.png" alt="">
        </div>
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

        margin-left: 20em;
         margin-right: 10em;
         max-width: 50%;
         display: flex;
}
.content{
    display: flex;
    margin-top: 40px;
}
.inner{
    text-align: center;
    justify-content: center;
    align-items: center;
    margin-left: 40px;
    width: 20em;
    height: 15em;
    padding: 10px;
    background: #fff;
    box-shadow: 1px 2px #a3d3ec;
    border-top: solid 1px #a3d3ec;
    border-radius: 5px;

}
h1{
    text-align: center;
}
p{
    text-align: center;
}
.para{
    width: 40em;
    line-height: 29px;
    padding-left: 60px;
}
.quest{
    background: #a3d3ec;
    padding: 20px;
    width: 90%;
    margin-top: -150px;
    margin-bottom: 40px;
    
}
.right{
    margin-left: 30px;
}
form{
    box-shadow: 1px 2px #a3d3ec;
    width: 100%;
    margin-bottom: 60px;
}
input{
    outline: none;
    border: none;
    height: 60px;
    padding-left: 30px;
    width: 80%;
}
textarea{
    width: 80%;
    height: 60px;
    padding-left: 30px;
    outline: none;
    border: none;
}
button{
        width: 80%;
        height: 50px;
        background: #0077b6;
        outline: none;
        border: none;
        border-radius: 10px;
        color: #fff;
        font-weight: bold;
        margin-left: 30px;
        margin-bottom: 40px;
        margin-top: 40px;
    }

     @media screen and (max-width: 480px) {
         .general{
         display: flex;
         flex-direction: column;
         max-width: 0px;
         margin-left: -10px;
         
}
    h1{
    text-align: center;
    width: 250px;
    padding-left: 80px;
}
p{
    text-align: center;
    width: 150px;
    padding-left: 100px;
}
    .para{
    width: 40em;
    line-height: 29px;
    text-align: left;
    width: 350px;
}
.content{
    display: flex;
    flex-direction: column;
    margin-top: 40px;
}
.right{
    display: none;
}
}
</style>


