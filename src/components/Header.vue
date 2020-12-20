<template>
  <div class="container-fluid">
    <h1>{{msg}}</h1>
    <!-- @include('public.layouts.logo') -->
<!--      <div class="logo col-md-1" id="logo">-->
<!--        <a href=""> <img src="./assets/logostd.png" style="width: 120px;"></a>-->
<!--      </div>-->
    <div class=" border border-dange col-md-9" id="sp">
      <div class="row">
        <li class="mac">
          <a  class="nav-link" href=""> Home</a>
        </li>
        <li class="mac">
          <a  class="nav-link" href=""> IPhone</a>
        </li>
        <li class="mac">
          <a  class="nav-link" href=""> IPad</a>
        </li>
        <li class="mac">
          <a  class="nav-link" href=""> MacBook</a>
        </li>
        <li class="mac" >
          <a class="nav-link" href=""> <span class="sr-only"></span></a>
        </li>
        <li class="mac">
          <a class="nav-link" href=""> Login</a>
        </li>
        <a href="">
          <i class="fa fa-cart-plus" style="font-size:48px;color:#ff0000"></i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "Header.vue",
  props: {
    msg: String
  }
}
</script>

<style scoped>



</style>