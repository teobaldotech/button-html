# button-html
button clickable
<!DOCTYPE html>
<html>
  <style>
    body{
      text-align: center;
    }


  </style>
<body>

<h2>affirmation block</h2>


<p>block</p>



<button type="button" onclick="myFunction()">Click Me!</button>



<p id="demo1"></p>
<p id="demo2"></p>

<script>
function myFunction() {
  
  document.getElementById("demo1").innerHTML = "Hello !";
  
}
