
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio Web </title>
 <style>
* {
 margin: 0%;  
padding: 0%;
box-sizing: border-box;
font-family: 'Poppins', sans-serif;
}




body {
background-image: url(back.webp) ;
background-repeat: no-repeat;
background-position: center;
background-attachment: fixed;
background-size: cover;
}
h2 {
 font-weight: bolder;
 font-size: 40px;
 margin-top: 20px;
 font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
 text-align: center;
 justify-content: center;

}
p{
 font-weight: bolder;
 font-size: 18px;
 margin: 10px auto;
 max-width: 300px;
 font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
 text-align: center;
 justify-content: center;

}
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    border-radius: 50%;  
    width: 250px;
     height: 250px; ;
}
.card{
    margin-left: auto;
    margin-right: auto;
    margin-top: 30px;
    margin-bottom: auto;
    width: 90%;
    max-width: 440px;
    color: #fff;
    text-align: center;
    padding: 50px 35px;
    border: 1px solid rgba(255,255,255,0.3);
    background: rgba(255,255,255,0.2);
    border-radius: 16px;
    box-shadow: 0 4px 30px rgba(0,0,0,0.1);
    backdrop-filter: blur(5px);
}
.card .links img{
          width: 50px ;
           height: 50px;
          border-radius: 50%;
          margin: 10px 5ps;
         display: inline-block;
         transition: background 0.5s;
        }
.card .links img:hover {
background: #ff01cf;

}
.btn{
 text-decoration: none;
 display: inline-block;
 font-size: 18px;
 font-weight: 500;
 background: #fff;
 color: #ff01cf;
 padding: 10px 30px ;
border-radius: 30px;
margin: 30px 0 10px;
font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
    </style>

</head>
<body>
<div class="container">
<div class="card" data-tilt>
<img src="profile.jpeg">
    <h2>Hacker Chuck</h2>
    <p >He is my favourite technical youtuber. I lave his videos about hacking.</p>
       <div class="links">
      <a href="https://facebook.com"><img src="facebook.jpeg"></a>
      <a href="https://twitter.com"><img src="twitter.webp"></a>
      <a href="https://instagram.com"><img src="insta.webp"></a>
       
    </div>
 <a href="#" class="btn">message me </a>
</div>
</div>

<script src="vanilla-tilt.js"></script>
</body>
</html>
