# fridhemshemsida
this is my first webpage
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html" charset="iso-8859-1">
    <title>My web project</title>
    <style>
    
   h1{
  color:white;
  background-color:black;
  text-align: center;
    font-size: 80px;
    padding: 80px;
    width: 100%;
}
.toppbild{
  /*flexbox*/
   display: flex;
   align-items: top;
   justify-content: center;
 }
img{
  border: 10px solid black;
}
.infoknappar{
  /*flexbox*/
  display: flex;
  justify-content: center;
  align-items:center;
  /*styling*/
  width: 100%;
  height: 400px;
  text-align: center;
  background-color: white;
}
.infoknapptext{
  width: 200px;
  height: 50px;
  margin: 50px;
  background-color: black;
  color:white;
  font-size:30px;
  padding: 40px; 	
}
.justnurubrik{
   color:white;
  background-color:black;
  text-align: center;
    font-size:90px;
    padding: 50px;
    width: 100%;  
  }
.justnu{
  color:black;
  background-color:white;
  font-size:80px;
  margin left: 200px;
  widht: 100%;
  padding:50px;
}

    </style>
  </head>
  <body>
  
<h1>Fridhems samfällighet</h1>
<div class="toppbild">
  <img class="toppbild1" src="https://images.unsplash.com/photo-1516156008625-3a9d6067fab5?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=47b4b88e2825332da6fb93898562051c&auto=format&fit=crop&w=1350&q=80" alt="Bild på hus" />
<img img class="toppbild1" src="https://images.unsplash.com/photo-1516399779-1480b4f76df6?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=91d3888b79d5fd667ad03f5833e89d45&auto=format&fit=crop&w=750&q=80" alt="Bild på katt" />
<img img class="toppbild1" src="https://images.unsplash.com/photo-1474649107449-ea4f014b7e9f?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=ee665399b33bc893141af2bc7bb87333&auto=format&fit=crop&w=1350&q=80" alt="Bild på keps" />
</div>


  <div class="infoknappar">
  <div class="infoknapptext">Måste info</div>
    <div class="infoknapptext">Bra info</div>
      <div class="infoknapptext">Onödig info</div>
</div>
  
<div class="justnurubrik">
  <div class="justnurubrik"> Vad händer</div>

<div class="justnu">
 <div class="justnu">STÄDDAG! Kom den 14 oktober, du behövs</div>
  <div class="justnu">SOPRUMMET! Städning behövs,  <a href="https://polisen.se/"> intresseanmälan görs här</></a></div>
</div>
 
<div class="vadtyckerdu">
    <img class="vadtyckerdu" src="https://images.unsplash.com/photo-1484069560501-87d72b0c3669?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=f0a61f73dbc747e7d9907bbfa8a87c45&auto=format&fit=crop&w=1350&q=80"/>

  <div class="vadtyckerdutext">
    <div class="vadtyckerdutext">Vad tycker DU?</div>
  </div>
  

  <html>

<head>
  <script>
    function getVote(int) {
      if (window.XMLHttpRequest) {
        // code for IE7+, Firefox, Chrome, Opera, Safari
        xmlhttp = new XMLHttpRequest();
      } else { // code for IE6, IE5
        xmlhttp = new ActiveXObject("Microsoft.XMLHTTP");
      }
      xmlhttp.onreadystatechange = function() {
        if (this.readyState == 4 && this.status == 200) {
          document.getElementById("poll").innerHTML = this.responseText;
        }
      }
      xmlhttp.open("GET", "poll_vote.php?vote=" + int, true);
      xmlhttp.send();
    }
  </script>
</head>

<body>

  <div id="poll">
    <h3>Ärtsoppa eller Gulash på städdagen?</h3>
    <form>
      Ärtsoppa med punsh:
      <input type="radio" name="vote" value="0" onclick="getVote(this.value)">
      <br>Gulash med styrketår:
      <input type="radio" name="vote" value="1" onclick="getVote(this.value)">
    </form>
  </div>

</body>

</html>
  <h3>5 måsten varje medlem måste göra</h3>
  <p>1 HÄLSA PÅ DEM MAN MÖTER</p>
  <p>2 VAR SNÄLL MOT BARN <p>3 VAR SNÄLL MOT KATTER <p>4 KOM PÅ STÄDDAGAR </p>5 HÅLL RENT I SOPRUMMET </p>

  </body>
</html>
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
