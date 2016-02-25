# chiaramagliacane.github.io
first_site
<!DOCTYPE html>
<html lang="en">
<head>
  <script src="https://dash.generalassemb.ly/assets/jquery.js"></script>
  <link href="/normalize.css" rel="stylesheet">
   <link rel="stylesheet" href="hello2.css" type="text/css">
   <link href='https://fonts.googleapis.com/css?family=Indie+Flower' rel='stylesheet' type='text/css'>
   <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
  <nav>
    <div class='navbar'>
      <div class="container">
        <div class="navbar-header">
          <ul class="navbar-left">
            <li><a ref="#">Closed Circle</a></li>
          </ul>
</div>
        
        <div class="navbar-collapse">
          <ul class="navbar-right">
            <li><a href="./about.html">Contact Us</a>
          </ul>
        </div>
        <div class="clear"></div>
        </div>
    </div>
  </nav>

  <header>
    <img src="http://i.imgur.com/fJfX7HE.jpg">
    <h1>Closed Circle</h1>
    <h2>Stories for everyone who wants to read</h2>
    <ul>
      <li><a href="#">About</a></li>
      <li><a href="#">Stories</a></li>
      <li><a href="#">Poems</a></li>
      <li><a href="#">Essays</a></li>
    </ul>
  </header>
  <article>
    <link href='https://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
    <div class='row'>
    <div class='col-sm-4'>
    <div class="first">
    <p>Presentare i personaggi<br />
      <small>Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</small></p>
    </div>
  </div>
  <div class='col-sm-4'>
    <div class="second">
    <p>brother<br /><small>Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</small></p>
  </div>
  <div class='col-sm-4'>
  <div class="third">
<p>sister<br /><small>Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</small></p>
</div>
</div>
</div>
  </article>


</body>
</html>


CSS:
header {
      max-width: 1500px;
      text-align: center;
      background: url('https://images.unsplash.com/photo-1432821596592-e2c18b78144f?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&s=3f9c78df0edb464244bbabb04d1797d8');
      background-size: cover;
      color: rgba(1,50,32,1);
      margin: 65px 45px;
      font-family: 'Indie Flower', cursive;
    }
    a {
      color: white;
      text-decoration: none;
    background-color: transparent;
    }
    h1 {
      font-size: 70px;
      margin: 0;
      padding: 0;
      height: 85px;
      width: 475px;
      background: rgba(255,255,255, 1);
      background: linear-gradient(bottom, rgba(255,255,255,1), rgba(255,255,255,.4));
      background: -webkit-linear-gradient(bottom, rgba(255,255,255,1), rgba(255,255,255,.4));
      background: -moz-linear-gradient(bottom, rgba(255,255,255,1), rgba(255,255,255,.4));
      border-radius: 100px 20px 100px 100px;
    }
    img {
      margin: 40px 0 0 0;
      border: 7px solid white;
      border-radius: 100px 100px 100px 20px;
    }
    h2 {
      font-size: 45px, cursive;
      margin: 0;
      padding: 20px 0 0 0;
      height: 50px;
      width: 475px;
      background: rgba(255,255,255, 1);
       background: linear-gradient(bottom, rgba(255,255,255,1), rgba(255,255,255,.4));
  background: -webkit-linear-gradient(bottom, rgba(255,255,255,1), rgba(255,255,255,.4));
  background: -moz-linear-gradient(bottom, rgba(255,255,255,1), rgba(255,255,255,.4));
      border-radius: 0 100px 100px 0;
    }
    body {
      background: rgba(255,255,255, 1);
      margin: 0 auto;
    }
    article {
      max-width: 600px;
      width: 600px;
      margin: 0 auto;
      padding: 20px 0;
      font-family: 'Open Sans', sans-serif;
    }
    p {
      color: rgba(255,255,255,1);
      background: black;
      background: linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
      background: -webkit-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
      background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
      padding: 10px;
      line-height: 28px;
      text-align: justify;
      position: absolute;
      bottom: 0;
      margin: 0;
      height: 150px;
      transition: height .5s;
      -webkit-transition: height .5s;
      -moz-transition: height .5s;
    }
    ul {
      padding: 10px;
      background: rgba(0,0,0,0.5);
    }
    li {
      display: inline;
      padding: 0 10px 0 10px;
    }
    small {
      opacity: 0;
}
/*
div {
    display: block;
}
*/
nav {
  color: rgba(255,255,255,1);
  text-align: center;
  background-color: rgba(1,50,32,0.7);
  height: 65px;
  width: 100%;
  margin: 0 auto;
  font-size: 25px;
  font-family: 'Indie Flower', sans-serif;
}
/*
.row {
  display: inline;
}*/

.navbar {
    position: fixed;
    right: 0;
    left: 0;
    display: inline;
}
.container {
  background: rgba(1,50,32,1);
  /*
  height: 50px;*/
  height: 65px;
  width: 100%;/*
  margin: 0 auto;*/
    text-align: center;/*
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;*/
    
    display: table;/*
    display: inline;*/
}
/*
.clear {
    clear:both;
    }*/

.navbar-header {
/*
  height: 50px;
  width: 300px;*/
  margin-right: 10px; /*
  padding: 10px auto; */
  clear:left;
}

.navbar-left {
  background-color: rgba(1,50,32,1);
  height: 50px;
    width:280px;/*
    height:auto;*/
    float:left;
    margin-bottom:10px;
    padding: 0;
}
.navbar-right {
background-color: rgba(1,50,32,1);
  height: 50px;
    width:280px;/*
    height:auto;*/
    float:left;
    margin-bottom:10px;
    padding: 0;
}
.nav > li > a {
    position: relative;
    display: block;
    padding: 10px 15px;
}

.first{
  background-image: url("http://i.imgur.com/coBdnjp.jpg");
  height: 300px;
      background-size: cover;
      position: relative;
      margin: 40px 0 0 0;
      border-radius: 12px;
}
.second{
  background-image: url("http://dash.ga.co/assets/secondcourse.jpg");
  height: 300px;
      background-size: cover;
      position: relative;
      margin: 40px 0 0 0;
      border-radius: 12px;
}
.third{
  background-image: url("http://dash.ga.co/assets/secondcourse.jpg");
  height: 300px;
      background-size: cover;
      position: relative;
      margin: 40px 0 0 0;
      border-radius: 12px;
}
