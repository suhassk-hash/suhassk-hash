<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title > Suhas Koheda Photography Landing Page </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Kalam&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./style.css">
    <link rel="apple-touch-icon" sizes="180x180" href="./Icons/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="./Icons/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="./Icons/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
  style{
  body{
    color: black;
}
.Main-Page-Headings{
    text-align: center;
    font-size: larger;
  }
  .Main-Page-Paragraphs{
    text-align: center;
    font-weight: 600;
    font-size: large;
  }
  p{
      font-size: medium;
  }
  .Social-Icons li{
    display: inline-block;
  }
  .Social-Icons {
    text-align: center;
  }
  .First-Page-Icon{
    width: 30px;
    height: 30px;
  }
  .Nav-Icon{
    width: 30px;
    height: 30px;
    border-color: blue;
  }
.header-text{
    color: black;
    font-family: kalam;
    text-align: center;
    font-weight: 400;
    filter: drop-shadow(10px 10px 10px black );
    -webkit-filter: drop-shadow(10px 10px 10px black );
}
.Insta-btn{
    font-family: kalam;
    text-transform: capitalize;
}
.Web-btn{
    font-family: kalam;
    text-transform: capitalize;
}
.Git-btn{
    font-family: kalam;
    text-transform: capitalize;
    
}
.column{
    float:center;
    text-align: center;
    font-family: kalam !important;
    font-weight: 1000;
    font-size: x-large;
  }
  .row::after{
    content:"";
    clear:both;
    display:table
  }
  @media screen and (max-width:500px){
    .column{
      width:100%
    }
}
button{
    width: fit-content;
    font-size: larger;
}
img{
    border-radius: 50%;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    -ms-border-radius: 50%;
    -o-border-radius: 50%;
    border-style:solid;
    border-color:red;
}
  }
</head>
<body>
    <h2 class="header-text">Suhas Koheda Photography</h2>
    <br>
    <div >
        <div class="column">
          <img src="./profilephoto.jpg" alt="">
        </div> <br>
        <div class="column">
            <div>
                <h1 class="Main-Page-Headings">About Suhas</h1>
                <p class="Main-Page-Paragraphs">Suhas is a photographer from India. <br>He loves to capture Wildlife and also loves to travel around the world </p>
              </div> 
              <br>
              <div class="Social-Icons">
                <li><a class="active" href="https://bit.ly/skp-website" target="_blank"><img src="./Web-Icons/icons8-website-30.png" class="Nav-Icon" alt=""></a><p>My Website</p> </li>
                <li><a class="active" href="https://bit.ly/skp-prints" target="_blank"><img src="./Web-Icons/icons8-print-30.png" class="Nav-Icon" alt=""></a><p>Buy Prints</p> </li>
                <li><a class="active" href="https://bit.ly/skp-presets" target="_blank"><img src="./Web-Icons/icons8-dng-48.png" class="Nav-Icon" alt=""></a><p>Buy Presets</p> </li><br>
                <li><a class="active" href="https://bit.ly/skp-instagram" target="_blank"><img src="./Web-Icons/icons8-instagram.gif"  class="Nav-Icon" alt=""></a><p>My Instagram</p> </li>
                <li><a class="active" href="https://bit.ly/skp-500px" target="_blank"><img src="./Web-Icons/icons8-500px-32.png"  class="Nav-Icon" alt=""></a><p>My 500px - Account</p> </li>
                <li><a class="active" href="https://bit.ly/skp-mail"target="_blank"><img src="./Web-Icons/icons8-mail-24.png" class="Nav-Icon" alt=""></a> <p>G-Mail Me</p></li><br>
                <li><a class="active" href="#"target="_blank"><img src="./Web-Icons/icons8-twitter (1).gif" class="Nav-Icon" alt=""></a><p>My Twitter</p> </li>
                <li><a class="active" href="#"target="_blank"><img src="./Web-Icons/icons8-facebook-80.png" class="Nav-Icon" alt=""></a> <p>My Facebook</p></li>
                <li><a class="active" href="https://bit.ly/skp-github" target="_blank"><img src="./Web-Icons/icons8-github.gif" class="Nav-Icon" alt=""></a><p>My Github</p> </li><br>
               
            </div>
        </div>
</div>
</body>
</html>
