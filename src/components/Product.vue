<template>
<div class=" ">  
   <div class="collection">
       <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630356346/e%20commerce/obj_3_1_lpnefj.png" alt="">
      </div>
        <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630328202/e%20commerce/obj_3_1_lpnefj.png" alt="">
      </div>
        <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630328202/e%20commerce/obj_3_1_lpnefj.png" alt="">
      </div>
        <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630328202/e%20commerce/obj_3_1_lpnefj.png" alt="">
      </div>
     
</div>      
  <div class="btn-area"><button>GET STARTED</button></div>

     </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.collection{
  display: flex;
  position: relative;
  scroll-behavior: smooth;
  z-index: 2;
  overflow-x:auto;
  margin: auto 0px;
  
}
.image{
display: inline-block;
background: #ffffff;
    text-align: center;
    padding:50px 0px;
    margin:30px 20px 30px 20px;
}
.image img{

}
.btn-area {
  text-align: center;
  margin-top: 90px;
}
button {
  font-size: 20px;
  padding: 22px 90px;
  background: #ff5101;
  border: none;
}

button:hover {
  background: #fd621b;
}

@media (min-width: 1200px) {
 .image img{
     justify-content:center;
         min-width:280px;

 }
}

@media (max-width: 768px) {
 .image {
   min-width: 155px !important;
  
         img{
     max-width: 50px;
        }
 }
}

</style>