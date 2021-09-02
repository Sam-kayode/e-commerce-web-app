<template>
<div><div class="trend-nav mt-4 text-center">
       <a href="" class="mx-3">Skincare</a>
       <a href="" class="mx-3">Make-up</a>
       <a href="" class="mx-3">Body</a>
       <a href="" class="mx-3">Hair</a>
  </div>
  <div class="products">
     <Product/>
  </div>
  </div>
      
</template>

<script>
import Product from "@/components/Product.vue"


export default {

components:{Product}
}
</script>

<style lang="scss">
.trend-nav{
a{
    color: #ABABAB;

}
a:hover{
    color:black;
    transition: 0.6s ease-out;
}
}
</style>