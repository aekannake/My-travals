# My-travals
Web technology
HTML CODE:

<!DOCTYPE html>
<html>
<head>
    <title> Travel Booking</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
    <header>
        <div class="main">
            <div class="logo">
                <img src="logo.png">
            </div>
            <ul>
                <li class="active"><a href="#"> HOME </a></li>
                <li><a href="#">SERVICES</a></li>
                <li><a href="#"> GALLERY </a></li>
                <li><a href="#"> ABOUT </a></li>
                <li><a href="#"> HELP </a></li>
            </ul>
        </div>
        <div class="title">
            <h1> Travels Booking</h1>
        </div>
        <div class="button">
             <a href="index2.html" class="btn">Today Travels</a>
            <a href="index3.html" class="btn">Tomorrow Travels</a>
        </div>
    </header>
</body>
</html>




*{
    margin: 0;
    padding: 0;
    font-family: Century Gothic;
}
 
header{
    background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url(../1.jpg);
    height: 100vh;
    background-size: cover;
    background-position: center;
}
 
ul{
    float: right;
    list-style-type: none;
    margin-top: 25px;    
}
 
ul li{
    display: inline-block;
}
 
ul li a {
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    border: 1px solid transparent;
    transition: 0.6s ease;
}
 
ul li a:hover{
    background-color: #fff;
    color: #000;
}
 
ul li.active a{
    background-color: #fff;
    color: #000;
}
 
.logo img{
    float: left;
    width: 150px;
    height: auto;
}
 
.main{
    max-width: 1200px;
    margin: auto;
}
 
.title{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}
 
.title h1{
    color: #fff;
    font-size: 50px;
}
 
.button{
    position: absolute;
    top: 60%;
    left: 50%;
    transform: translate(-50%,-50%);
}
 
.btn{
    border: 1px solid #fff;
    padding: 10px 30px;
    color: #fff;
    text-decoration: none;
    transition: 0.6s ease;
}
 
.btn:hover{
    background-color: #fff;
    color: #000;
}

