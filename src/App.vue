<template>
  <div id="app">
    <nav> <h1>Secret Santa </h1></nav>


    <div class="authContainer">
      <div class="leftSide">
        <h2 class="signup"> Sign Up</h2> 
      </div>

      <div class="rightSide">
        <h2 class="login"> Log in </h2>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
#app {
  text-align: center;

}

.authContainer {

}

.leftSide {
  float: left;
  border: 1px solid black;
  text-align: center;
}
.rightSide {

}
.signup {
  float: right;

  text-align: center;
}

.login {

}
</style>
