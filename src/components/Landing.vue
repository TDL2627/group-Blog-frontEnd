<template>
  <div id="landing">

    <h1 class="animate__animated animate__bounce">SUPER BLOG</h1>

    <div class="container">
      <div class="row">
    <div class="col-lg-6">
        <router-link to="/login">LOG IN</router-link>
      </div>
           <div class="col-lg-6">
        <router-link to="/signup">SIGN UP</router-link>
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
#landing{
  padding-top:10% ;
}
.container{
  padding-top: 20%;
}
a{
  text-decoration: none;
  border: 2px solid black;
  padding: 20px;
}
</style>