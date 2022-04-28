<template>
  <div id="login">

      <h1>LOGIN</h1>
<form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
 <!-- <button type="submit" class="btn btn-primary">Submit</button> -->
  <button  class="btn btn-primary"><router-link to="/blogs">SUBMIT</router-link> </button>
</form>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
form{
    border: 5px solid black;
    margin: 5%;
    padding: 5%;
}
a{
    text-decoration: none;
    color: white;
}
</style>