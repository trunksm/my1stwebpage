
<html>
<head>
<title>GAMESTORM</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
</head>

<style>


  .carousel-inner > .item > img,
  .carousel-inner > .item > a > img {
      width: 35%;
      margin: auto;
 
  }
 
h1 {color:blue; font-size:20px;text-align:right}

div.img {
    margin: 20px;
    border: 1.5px solid white;
    height: auto;
    width: auto;
    float: left;
    text-align: center;
}	

div.t{
color: white;
font-weight: normal;
text-align:right;
}
div.back{
text-align:center;
}
div.para{
text-align:center;
font-family:arial;
font-size:20;

}
div.about{

text-align:right;
}

div.img img {
    display: groove;
    margin: 0px;
    border: 1px solid #ffffff;
}

div.img a:hover img {
    border: 5px solid #F8F8F8 ;

}


div.desc {
  text-align: center;
  font-weight: normal;
  width: 120px;
  margin: 5px;
}
div.text{
text-align:center;
color: white;
background-color:#33FFFF;
width :95%;
height: 30px;
padding:30px;
border:1px white;

font-size:6;
}

div.free{
text-align:right;
color: #FFFF66;
margin: 5px;
}

a.ex1:hover, a.ex1:active {font-family: broadway;}
a.ex2:hover, a.ex2:active {font-family: broadway;}
a.ex3:hover, a.ex3:active {font-family: broadway;}
a.ex4:hover, a.ex4:active {font-family: broadway;}
a.ex5:hover, a.ex4:active {font-family: broadway;}
a.ex6:hover, a.ex4:active {font-family: broadway;}
a.ex7:hover, a.ex4:active {font-family: broadway;}
a.ex8:hover, a.ex4:active {font-family: broadway;}


</style>
<body background="back.jpg">

<fieldset>
<img src="2.png" alt="animated image" style="width:320px;height:100px;">
<br><br>



<table cellspacing="10">
<tr>
<th><a class="ex1" href=""><font color="white">Home</th></a></font>
<th><li class="dropdown"><a class="ex1" href=""><font color="white">category<span class="caret"></span> </a></font>
</th>
<th><li><a class="ex1" href="a.html"><span class="glyphicon glyphicon-user"></span><font color="white">sign in</li></th></a></font>
<th><a href=""><button type="button" class="btn btn-info"><span class="glyphicon glyphicon-search"></span> Search</a></th>
</tr>
</table>
<br><br><br><br><br>
<font size="5" color="white"><U>Editor's Choice</U></font>
<div class="container">
  <br>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">

      <div class="item active">
        <img src="mmm.png" alt="Chania" width="12" height="10">
        <div class="carousel-caption">
        
          <h3><B>MMM Fingers</B></h3>
          <p><B><font size="6">Dare To Play It.</B></font></p>
        </div>
      </div>

      <div class="item">
        <img src="Temple-Run.jpg" alt="Chania" width="12" height="10">
        <div class="carousel-caption">
          <h3>Temple Run</h3>
          <p><B><font size="6">Endless Run.</B></font></p>
        </div>
      </div>
    
      <div class="item">
        <img src="c.png" alt="Flower" width="12" height="10">
        <div class="carousel-caption">
          <h3>Clash Of Clans</h3>
          <p><B><font size="6">Giant is Ready To Play.</B></font></p>
        </div>
      </div>

      <div class="item">
        <img src="candycrush.jpeg" alt="Flower" width="12" height="10">
        <div class="carousel-caption">
          <h3>Candy Crush</h3>
          <p><B><font size="6">Delicious Candies Are </B></font></p>
          <p><B><font size="6">Waiting For You </B></font></p>
        </div>
      </div>
      <div class="item">
        <img src="subways.png" alt="Flower" width="12" height="10">
        <div class="carousel-caption">
          <h3>Subway Surfers</h3>
          <p><B><font size="6">Run Over The Train </B></font></p>
          
        </div>
      </div>
      <div class="item">
        <img src="monument.png" alt="Flower" width="12" height="10">
        <div class="carousel-caption">
          <h3>Monument</h3>
          <p><B><font size="6">Play To Win It </B></font></p>
        
        </div>
      </div>
     <div class="item">
        <img src="duet.png" alt="Flower" width="12" height="10">
        <div class="carousel-caption">
          <h3>Duet</h3>
          <p><B><font size="6">Turn Down The Obstacles</B></font></p>
        
        </div>
      </div> 
     <div class="item">
        <img src="cut.png" alt="Flower" width="12" height="10">
        <div class="carousel-caption">
          <h3>Duet</h3>
          <p><B><font size="6">Save him to win it</B></font></p>
        
        </div>
      </div> 
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<font size="6" color="yellow"><U>POPULAR GAMES :</U></font><br>
<font size="3" color="yellow"><U>Selected Games Weekly Updated</U></font><br>
<br>
<fieldset>

<div class="img">
 <a target="_blank" href="google.com"><img src="subways.png" alt="subway surfer" width="190" height="190"></a>
 <div class="desc"><U><a class="ex1" href="default.asp"><font color="white">
 <a href="#demo2" class="btn btn-info" data-toggle="collapse">Subway surfer</a>
  <div id="demo2" class="collapse">
DASH as fast as you can! 
DODGE the oncoming trains!
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.83">83%</meter>
<div class="free"><B>Free</B></div>
</div>

<div class="img">
 <a target="_blank" href="google.com"><img src="candycrush.jpeg" alt="Candy Crush" width="190" height="190"></a>
 <div class="desc"><U><a class="ex2" href="default.asp"><font color="white">
 <a href="#demo3" class="btn btn-info" data-toggle="collapse">Temple Run</a>
  <div id="demo3" class="collapse">
crush the delicious candies by matching the pair of three or more....
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.80">80%</meter>
<div class="free"><B>Free</B></div>
</div>

<div class="img">
 <a target="_blank" href="google.com"><img src="temple-run.jpg" alt="Temple Run" width="190" height="190"></a>
 <div class="desc"><U><a class="ex3" href="default.asp"><font color="white">
 <a href="#demo" class="btn btn-info" data-toggle="collapse">Temple Run</a>
  <div id="demo" class="collapse">
run fast...otherwise you will be killed..
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.57">57%</meter>
<div class="free"><B>Free</B></div>
</div>

<div class="img">
 <a target="_blank" href="google.com"><img src="c.png" alt="Clash of Clans" width="190" height="190"></a>
 <div class="desc"><U><a class="ex4" href="default.asp"><font color="white">
<a href="#demo1" class="btn btn-info" data-toggle="collapse">clash of clans</a>
  <div id="demo1" class="collapse" >
From rage-­filled Barbarians with glorious mustaches to pyromaniac wizards, raise your own army and lead your clan to victory! 
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.6">60%</meter>
<div class="free"><B>Free</B></div>

</div>

</fieldset>
<br>
<br>
<font size="5" color="yellow"><U>TOP FREE GAMES :</U></font><br>
<font size="3" color="yellow"><U>Dont miss this hot titles</U></font><br>
<br>
<fieldset>
<div class="img">
 <a target="_blank" href="google.com"><img src="cut.png" alt="Cut The Rope" width="190" height="190"></a>
 <div class="desc"><U><a class="ex5" href="default.asp"><font color="white">
<a href="#demo4" class="btn btn-info" data-toggle="collapse">Cut The Rope</a>
  <div id="demo4" class="collapse" >
 the candy hangs by one or several of the titular ropes which the player must cut with a swipe of their finger using the device's touchscreen.
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.75">75%</meter>
<div class="free"><B>Free</B></div>
</div>

<div class="img">
 <a target="_blank" href="google.com"><img src="duet.png" alt="Duet" width="190" height="190"></a>
 <div class="desc"><U><a class="ex6" href="default.asp"><font color="white">
<a href="#demo5" class="btn btn-info" data-toggle="collapse">Duet</a>
  <div id="demo5" class="collapse" >
Players control two coloured orbs, guiding them to avoid incoming obstacles.
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.66">66%</meter>
<div class="free"><B>Free</B></div>
</div>

<div class="img">
 <a target="_blank" href="google.com"><img src="mmm.png" alt="MMM Fingers" width="190" height="190"></a>
 <div class="desc"><U><a class="ex7" href="default.asp"><font color="white">
<a href="#demo6" class="btn btn-info" data-toggle="collapse">MMM Fingers</a>
  <div id="demo6" class="collapse" >
Touch and hold the screen as long as you can. Don’t lift your finger or hit anything with teeth or else CHOMP, it is game over.
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.87">87%</meter>
<div class="free"><B>Free</B></div>
</div>

<div class="img">
 <a target="_blank" href="google.com"><img src="monument.png" alt="Monument Valley" width="190" height="190"></a>
 <div class="desc"><U><a class="ex8" href="default.asp"><font color="white">
<a href="#demo7" class="btn btn-info" data-toggle="collapse">Monument Valley</a>
  <div id="demo7" class="collapse" >
The player leads the princess Ida through mazes of optical illusions and impossible objects.
</div></font></a></U></div>
<div class="rating"><font color="white">
<span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span><span>&#9733</span></font>
</div>
<br>
<meter value="0.92">92%</meter>
<div class="free"><B>Free</B></div>
</div>
</fieldset>

</fieldset>
</fieldset>
<fieldset>
<div class="about"><b><a class="ex1" href="p.html"><font color="white">About</a></font></b></div><br><b><a class="ex1" href=""><font color="white">Feedback</b></font></a>&nbsp&nbsp&nbsp<b><a class="ex1" href=""><font color="white">Help</b></font></a>&nbsp&nbsp&nbsp<b><a class="ex1" href=""><font color="white">Contact</b></a></font><br>
<b><a class="ex1" href=""><font color="white">Terms&Conditions<b></font></a><br>
<p><font color="white">Games and Apps on this website are original.While using this site ,you agree to have read and accepted our terms of use,cookie and privacy policies.Copyright 1999-2015 by ISO.All rights reserved</font></p>
<p><font color="white"><div class="about">shoaibmulla123@gmail.com</p></font></div>
</fieldset>
</body>
</html>
