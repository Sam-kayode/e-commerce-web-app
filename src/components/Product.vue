<template>
<div class="collection-containe">  
   <div class="collection">
       <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630356346/e%20commerce/obj_3_1_lpnefj.png" alt="">
      </div>
        <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630328203/e%20commerce/obj_1_1_zr9kkp.png" alt="">
      </div>
        <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630328202/e%20commerce/obj_4_1_rjnxnb.png" alt="">
      </div>
        <div class="image" >
          <img src="https://res.cloudinary.com/sam-kay/image/upload/v1630328202/e%20commerce/obj_2_1_zf90by.png" alt="">
      </div>
     
</div>      
  <div class="btn-area"><button>SHOP ALL TRENDING</button></div>
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid, voluptas. Expedita fugiat cumque accusamus explicabo suscipit labore ducimus eum, delectus asperiores fuga nulla, ipsam illum nesciunt exercitationem dolore? Eius, mollitia?

     </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.collection-container{
  margin: auto;

}
.collection{
  display: grid;
  position: relative;
  scroll-behavior: smooth;
  z-index: 2;
  overflow-x:auto;
    margin:auto;
 grid-template-columns:repeat(4, minmax(250px, 300px));

}
.image{
display: inline-block;
background: #ffffff;
    text-align: center;
    padding:50px 0px;
    height:fit-content;
    margin:30px 20px 40px 20px;
}
.image img{

}
.btn-area {
  text-align: center;
  margin-top: 30px;

button {
  font-size: 20px;
  padding: 22px 90px;
  background: #ff5101;
  border: none;
}

button:hover {
  background: #fd621b;
}
}

@media (min-width: 1200px) {
 .image
 { 
   justify-content: center;

   img{
    

 }
 }
}

@media (max-width: 768px) {
 .image {


         img{
    
        }
 }
 .btn-area {
 button {
  font-size: 18px;
  
  padding: 13px 42px;
  color:white;

}

}
}

</style>