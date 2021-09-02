<template>
  <div class="home">
    <div class="top-area">
      <p class="opening-text">
        Treat Your Skin Like <br />

        <em>A Goddess</em>
      </p>
      <h5 class="description">
        With kuro, you can get proper care of skin naturally <br />that has long
        lasting effect.
      </h5>

      <div class="btn-area"><button>GET STARTED</button></div>
    </div>
    <b-container fluid class="p-lg-5">
  <b-row>
    <b-col class="catcher p-sm-5 p-md-5" align-self="center" lg="3" order-lg="1" order="2"> WHERE SCIENCE <br> CO-EXISTS <br>WITH NATURE</b-col>
    <b-col class="catcher-img py-sm-3 py-sm-0" align-self="center" lg="6" order-lg="2" order="1"><img src="https://res.cloudinary.com/sam-kay/image/upload/q_auto:low/e%20commerce/ecommerce_1_hr82dj.png" alt=""></b-col>
    <b-col class="catcher-end px-sm-5 px-md-5" align-self="end" lg="3" order-lg="3" order="3"><p>Consectetur reprehenderit excepteur excepteur tempor voluptate deserunt exercitation mollit excepteur veniam voluptate dolor officia. Magna cupidatat ex esse velit magna sit incididunt cillum. Mollit eu in sint reprehenderit laborum ea eiusmod et nostrud eiusmod voluptate. Non magna occaecat culpa culpa aliquip. In sit voluptate eu non aute pariatur fugiat consectetur. Ut minim Lorem ipsum eiusmod id nostrud id ullamco in ad velit laboris. Pariatur tempor nostrud deserunt deserunt ullamco sint dolor laborum </p></b-col>
  </b-row>
  <div class="explore">
  <h1 class="text-center trending mt-5">Shop our Trending <br> Beauty products </h1>
  <p class="text-center trending-descr">Explore the clean beauty essentials</p>
  <Trending/>
</div>
</b-container>

  </div>
</template>

<script>
// @ is an alias to /src
import Trending from "@/components/Trending.vue"

export default {
  name: "Home",
  components: {Trending, },
};
</script>
<style lang="scss" scoped>
.home {
  .opening-text {
    margin-top: 0;
    padding-top: 234px;
    font-size: 96px;
    margin-bottom: 50px;
    font-weight: lighter;
    text-align: center;
    font-family: "Times New Roman", Times, serif;
  }
  .description {
    text-align: center;
    font-weight: normal;
    font-size: 25px;
    font-family: "Urbanist", sans-serif;
  }
  .trending{
    font-family: 'Times New Roman', Times, serif;
    font-size:48px;
  }
  .trending-descr{
    font-family: sans-serif;
   font-size:19px;
  }
}

.btn-area {
  text-align: center;
  margin-top: 90px;
}
button {
  font-size: 20px;
  padding: 22px 103px;
  background: #ff5101;
  border: none;
}

button:hover {
  background: #fd621b;
}

.top-area {
  color: white;
  padding-bottom: 120px;
  background: url("https://res.cloudinary.com/sam-kay/image/upload/q_auto:low/e%20commerce/generic-beauty-products-on-orange-coral-PEZHDXA_1_furoj5.png");
  background-size: cover;
}

.catcher{
font-family: 'Times New Roman', Times, serif;
font-style: normal;
font-weight: normal;
font-size: 40px;
line-height: 50px;
color: #1B262C;
}
.catcher-end{
  font-size: 12px;
}
.catcher-img{
text-align: center;
}
.catcher-img img{
  width:100%;
    text-align:center;
}


@media (max-width: 1110px) {
  .opening-text {
    font-size: 80px;
  }
 .catcher-img img{
 max-width:600px;
 
}
}

@media (max-width: 920px) {
  .opening-text {
    font-size: 70px;
  }
  .catcher-img{
  text-align:center;
  }
}

@media (max-width: 768px) {
  
  .opening-text {
    font-size: 60px;
  }


}

@media (max-width: 576px) {
 .opening-text {
    font-size: 45px !important;
  }
}
</style>
