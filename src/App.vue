<template>
  <div id="app">
    <nav> <h1>Secret Santa </h1></nav>

    <!-- One major div divided between left and right side divs -->
    <div class="authContainer"> 
      <div class="leftSide">
        <h2 class="signup"> Sign Up</h2>
        <div class="inputFields">
          <div class="form-group row">
            <div class="col-10">
              <input class="form-control" type="text" value="" placeholder="Santa Claus" id="example-text-input">
            </div>
          </div>
          <div class="form-group row">     
            <div class="col-10">
              <input class="form-control" type="email" value="" placeholder="santaclaus@thenorthpole.com" id="example-email-input">
            </div>
          </div>
          <div class="form-group row">
            <div class="col-10">
              <input class="form-control" type="password" value="" placeholder="Password" id="example-password-input">
            </div>
          </div>
          <div class="form-group row">
            <div class="col-10">
              <input class="form-control" type="password" value="" placeholder="Confirm Password" id="example-password-input">
            </div>
          </div>
            <!--Possibly add phone number here?-->
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
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
/*  border: 1px solid red;*/
  height: 100%;
}

.leftSide {
  float: left;
/*  border: 1px solid black;*/

  width: 50%;

}

.rightSide {
/*  border: 1px solid black;*/
}

.inputFields {
  width: 75%;
}


.signup {


}

.login {

}
</style>













