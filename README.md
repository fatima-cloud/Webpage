<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="Styles.css">
<title>IO Digital</title>

<a href style="float: right;"> WORK &nbsp; &nbsp; TEAM &nbsp; &nbsp; CONTACT &nbsp; &nbsp; CAREER</a>

<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
</head>

<body>


    <img src="./digital.png" alt="digital" />
    <h1 style="color:blue">Got an Idea? Lets build it. -> </h1>


    <marquee behavior="alternate">

        <div class="row">
        <div class="column">
        <img src="./toomuchwifi.png" alt="Wifi">
        <p>Too Much Wifi | Startup</p> 
        <a href="Case1">Case Study coming soon</a>
    
        </div>
        <div class="row">
        <div class="column">
        <img src="./client.jpg" alt="Client">
        <p>EIDO | Client</p>
        <a href="Case2">Case Study coming soon</a>
    
        </div>
        <div class="row">
        <div class="column">
        <img src="./gfm.jpg" alt="gfm">
        <p id="gfm-p">Green Fingers Mobile | Startup </p>
        <a href="Case3">Case Study coming soon</a>
    
        </div>
        </div>
        
        </marquee>
    
    



<y> Got an Idea? Lets build it. We build and develop tech innovations.</p>
 

<h3 id="io-heading" style="color:navy"><bold><center>IO | DIGITAL</h3></bold></h1 style></center>


<div id="app">
    {{ message }}
</div>


<script>

var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Fatima!!!!!'
  }
});

</script>

 <button style="background-color: navy; padding: 20px; color:white" onmouseover="hoverFunction()" onclick="changeColor('gfm-p', '#ff0')">Make the gfm text black!</button> 

 <script lang="javascript">
     var number = 0;
     console.log("1. number: ", number);

     number = number + 2;
     console.log("2. number: ", number);

     console.log("document", document.getElementById('io-heading').style.color ); //

    function definition
    ,function hoverFunction () {
        console.log("we're hovering!!"); 
    } 
    

     function changeColor(elementId, newColor) {
        console.log("changeColor is working!!")
        document.getElementById(elementId).style.color = newColor;
    }

    function hide(elementId) {
        document.getElementById(elementId).style.display = 'none';
    }

    // 0123456789abcdef
    // RGB == red green blue;
    // RRGGBB == red green blue;

    
    // e60    = organe
    // ff0    = yellow
    // ee22ee    = purple
    // 000000    = black
    // ffffff    = white

    // 666666    = white
    
    
    //intern to all web browse, ie, chrome, safari, opera
    // setTimeout(function(){
    //     changeColor("io-heading","#666666");
    // }, 5000); //1000 miliseconds == 1 second
        

    // setTimeout(function(){
    //     hide("io-heading");
    //     hide("gfm-p");
    // }, 10000); //1000 miliseconds == 1 second
        
</script> 

</body>


</html>
