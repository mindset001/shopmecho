<template>
    <div class="cover">
        <div >
           <div>
             <h1>GET IN TOUCH</h1>
           </div>
                <div>
                    <p>ADDRESS</p>
                    <h2>2 Ahmed Musa Street, Lakowe, Adeba Bus Stop, Lakowe, Lagos</h2>
                </div>
                <div>
                    <p>PHONE</p>
                    <h2>+234-8160 0712 43</h2>
                </div>
                <div>
                    <p>HOURS OF OPERATION</p>
                    <h2>MON—FRI: 8:00AM—5:30PM</h2>
                    <h2>SAT: 8:00AM—4:30PM</h2>
                    <h2>SUN: CLOSED</h2>
                </div>
        </div>

        
        <div >
             <GMapMap
      :center="center"
      :zoom="7"
      map-type-id="terrain"
      style="width: 500px; height: 300px"
      class="map"
  >
    <GMapCluster>
      <GMapMarker
          :key="index"
          v-for="(m, index) in markers"
          :position="m.position"
          :clickable="true"
          :draggable="true"
          @click="center=m.position"
      />
    </GMapCluster>
  </GMapMap>
        </div>
    </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      center: {lat: 6.434599, lng: 3.416209},
      markers: [
        {
          position: {
            lat: 6.434599, lng: 3.416209
          },
        }
        , // Along list of clusters
      ]
    }
  }
}
</script>

<style scoped>
    .cover{

        display: flex;
        
        padding-left: 20em;
        margin-top: 40px;
        background:  linear-gradient(
      rgba(104, 102, 102, 0.9), 
      rgba(243, 241, 241, 0.4)
    ), url('../assets/slide-3.jpg');
        background-size: cover;
        color: #fff;
        
    }
    .map{
        height: 500px;
        background-color: aqua;
        width: 72em;
        display: block;
    }
    h2{
        width: 400px;
    }
    h1{
        margin-top: 70px;
    }


    @media screen and (max-width: 480px) {
   
 .map{
     display: none;
 }
 .cover{

        display: flex;
        margin-left: -300px;
        margin-top: 40px;
        background:  linear-gradient(
      rgba(104, 102, 102, 0.9), 
      rgba(243, 241, 241, 0.4)
    ), url('../assets/slide-3.jpg');
        background-size: cover;
        color: #fff;
        
    }
      h2{
        width: 350px;
    }
    h1{
        margin-top: 70px;
    }
}
</style>
