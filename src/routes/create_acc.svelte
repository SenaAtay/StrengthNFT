<script>

import { blank_object } from "svelte/internal";

</script>
<!-- <h1 class = "title"> Stregthn</h1> -->



<h1 class = "intro"> Lets get started</h1> 


<!-- svelte-ignore a11y-missing-attribute -->
<html>
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box}

/* Full-width input fields */
input[type=text]{ 
position: absolute;
width: 456px;
height: 74px;
left: 732px;
top: 506px;

border: 2px solid #DBD3D2;
box-sizing: border-box;
border-radius: 9px;
}

 input[type=password]{
position: absolute;
width: 456px;
height: 74px;
left: 732px;
top: 592px;

border: 2px solid #D2D6DB;
box-sizing: border-box;
border-radius: 9px;
 }

input[type=fname]{
position: absolute;
width: 456px;
height: 73px;
left: 732px;
top: 328px;

border: 2px solid #D2D6DB;
box-sizing: border-box;
border-radius: 9px;
}

input[type=lname]{
position: absolute;
width: 456px;
height: 73px;
left: 732px;
top: 416px;

border: 2px solid #D2D6DB;
box-sizing: border-box;
border-radius: 9px;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

/* Set a style for all buttons */
button {
  background-color: #04AA6D;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 10%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

/* Extra styles for the cancel button */
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}

/* Float cancel and signup buttons and add an equal width */
.signupbtn {
    position: absolute;
width: 456px;
height: 73.55px;
left: 732px;
top: 708px;
background-color: black;

}

/* Add padding to container elements */
.container {
  padding: 16px;
}

/* Clear floats */
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

/* Change styles for cancel button and signup button on extra small screens */
@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
     width: 100%;
  }
}
</style>
<body>

<form action="/action_page.php" >
  <div class="container">
    <h1>Sign Up</h1>
    <p>Please fill in this form to create an account.</p>
   

    <label for="fname"><b></b></label>
    <input type="fname" placeholder="Enter First Name" name="fn" required>

    <label for="lname"><b></b></label>
    <input type="lname" placeholder="Enter Last" name="ln" required>

    <label for="email"><b></b></label>
    <input type="text" placeholder="Enter Email" name="email" required>

    <label for="psw"><b></b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <!-- <label for="psw-repeat"><b>Repeat Password</b></label>
    <input type="password_rep" placeholder="Repeat Password" name="psw-repeat" required> -->
    
    <!-- <label>
      <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
    </label> -->
    
    <!-- <p>By creating an account you agree to our <a href="#" style="color:dodgerblue">Terms & Privacy</a>.</p> -->

    <div class="clearfix">
      <!-- <button type="button" class="cancelbtn">Cancel</button> -->
      <button type="submit" class="signupbtn">Sign Up</button>
    </div>
  </div>
</form>

</body>
</html>

<style>
.title{
position:absolute;
width: 48px;
height: 71px;
left: 90px;
top: 70px;
}

.intro{
    
    position: absolute;
width: 266px;
height: 160px;
left: 732px;
top: 152px;

font-family: Roboto;
font-style: normal;
font-weight: 500;
font-size: 65px;
line-height: 123%;
/* or 80px */


color: #000000;
}

</style>