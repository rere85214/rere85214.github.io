<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<html>
<head>
<script src="//s3-ap-northeast-1.amazonaws.com/justfont-user-script/jf-34582.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="/jquery/jquery-1.11.1.min.js"></script>
<script>
  $(document).ready(function() {
    $("button").css("color", "#328DAA");
    $("button").css("background", "#F1BA48");
    $("#tofind").hide();
    $("button").click(function(){
      $("#tofind").fadeIn("3000");
    });
    $("button").mouseenter(function(){
      $("button").css("color", "#F1BA48");
      $("button").css("background", "#328DAA");
    });
    $("button").mouseleave(function(){
      $("button").css("color", "#328DAA");
      $("button").css("background", "#F1BA48");
    })
  });
</script>
</head>
<body background="https://s-media-cache-ak0.pinimg.com/564x/12/4e/3c/124e3c48e44a1f215254ea311c0eda36.jpg">
<style>
  h1 {
    font-family: Lobster, Monospace;
    color: #D75B66;
    font-size: 50px;
  }
  .img-border {
    border-color: #C1403D;
    border-width: medium;
    border-radius: 50%;
  }
  .absolute {
    position: absolute;
    right: 0;
    left: 0;
  }
  .relative {
    position: relative;
    top: 150px;
  }
  .relative2 {
    position: relative;
    left: 250px;
  }
  .relative3 {
    position: relative;
    left: 75px;
  }
  .center {
    text-align: center;
  }
  p {
    font-size: 20px;
    font-family: Monospace;
  }
  .border {
    border-color: #C1403D;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }
  .image {
    width: 500px;
  }
  .small-img {
    width: 100px;
  }
</style>
<div style="background-color: #23345C; background-size: cover" class="absolute">
<h1>Rere's Page</h1>
<marquee bgcolor="#F1BA48" behavior="altemate" style="font-family: Lobster, Monospace; font-size: 30px; color: #328DAA">Check out my information down below</marquee>
</div>

<div class="center relative">
  <img class="image img-border" alt="Rere's profile" src="https://scontent-tpe1-1.xx.fbcdn.net/v/t1.0-9/17498727_1259832560773732_1933983040341206493_n.jpg?oh=7362548ede6868731d6325a8c146db5a&oe=59575A14">
</div>

<div class="relative">
  <p class="relative2"><b>Name : </b></p>
  <h4 class="center" size="10px"><font face="微軟正黑體">錢姵文</font></h4>
  <p class="relative2"><b>Major : </b></p>
  <h4 class="center" size="10px"><font face="微軟正黑體">CSIE</font></h4>
  <p class="relative2"><b>Student ID : </b></p>
  <h4 class="center" size="10px"><font face="微軟正黑體">403262083</font></h4>
  <p class="relative2"><b>Nickname : </b></p>  
  <h4 class="center" size="10px"><font face="微軟正黑體">Rere</font></h4>
  <p class="relative2"><b>Find ME : </b>
  <button class="relative3"><font face="微軟正黑體"><b>CLICK TO FIND</b></font></button></p>
  <div id="tofind" class="center">
  <a href="https://www.facebook.com/profile.php?id=100002410016435"><img class="small-img" alt="facebook link" src="http://www.newdesignfile.com/postpic/2011/04/download-facebook-logo-for-website_51278.jpg" border="0"></a>
  <a href="https://www.instagram.com/rere85214/"><img class="small-img" alt="instagram link" src="http://www.freelogovectors.net/wp-content/uploads/2016/12/instagram-logo.png" border="0"></a></div>

</div>
</body>
</html>
