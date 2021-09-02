<template>
  <div class="navigation">
    <div class="left-nav">
      <a class="nav-items">SHOP</a>
      <a class="nav-items">OUR STORY</a>
      <a class="nav-items">JOURNAL</a>
    </div>
    <div class="center">KURO</div>
    <div class="right-nav">
      <a class="nav-items">FAQ</a>
      <a class="nav-items">BLOG</a>
      <a class="nav-items">ACCOUNT</a>
      <a class="nav-items-exp">Cart</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.navigation {
  color: white;
  display: grid;
  padding: 0;
  margin: 0;
  grid-template-columns: 40vw 20vw 40vw;
  margin-top: 10px;
  position: fixed;
  width:100vw;
  a{
        color:white;
  }
}



.center {
  text-align: center;
  font-family: "Cinzel", serif;
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 64px;
  cursor: pointer;
}

.left-nav {
  text-align: left;
  padding-top: 20px;
  a {
    margin-left: 60px;
    font-family: "Urbanist", sans-serif;
    font-style: normal;
    line-height: 14px;
    text-transform: uppercase;
    cursor: pointer;
  }
}

.right-nav {
  text-align: right;
  padding-top: 20px;
  a {
    margin-right: 60px;
    font-family: "Urbanist", sans-serif;
    font-style: normal;
    line-height: 14px;
    text-transform: uppercase;
    cursor: pointer;
  }
}

.nav-items {
}

@media (max-width: 1110px) {
  .left-nav {
    a {
      margin-left: 25px;
    }
  }
  .right-nav {
    text-align: right;
    a {
      margin-right: 25px;
    }
  }
}

@media (max-width: 920px) {
  .nav-items {
    display: none;
  }
  .navigation {
    grid-template-columns: 20vw 60vw 20vw;
  }
  .center {
    font-size: 36px;
  }
}
@media (max-width: 768px) {
  .center {
    font-size: 30px;
  }
}
@media (max-width: 576px) {
}
</style>
