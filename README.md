
#QR Code Card 
##IT IS MY FIRST PROJECT 
#First i learned HTML & CSS
#What were these : <head>,<body>,<h1>,<p>,<div>
  #Then learn how to make them move top to button, or left to right 
  #Also learn how to change color
  #Also learn how to change background
  #Also learn how to change font-size
  #Also meaninng of Box Model 
  #what was meaning and how was working <style>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>QR Code Card</title>
    <style>
      body {
        background-color: #f2f2f2;
        font-family: "Outfit", sans-serif;
      }

      div {
        width: 320px;
        background-color: white;
        border-radius: 20px;
        overflow: hidden;
        padding: 16px;
        margin: 0 auto;
        margin: 152px 260px;
      }
      h1 {
        color: #1f314f;
        font-weight: 700 em;
        text-align: center;
        font-size: 22px;
        font: bold;
      }
      p {
        color: #7d889e;
        font-weight: 400em;
        text-align: center;
        font-size: 15px;
      }
      img {
        max-width: 100%;
        border-radius: 10px;
      }
    </style>
  </head>
  <body>
    <div>
      <img src="image-qr-code.png" />
      <h1>
        Improve your front-end skills by building projects
      </h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </body>
</html>

