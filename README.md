<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>protofolio</title>
    <link rel="stylesheet" href="protofolio.css">
    <style>
          *{
    margin: 0;
    padding:0;
    font-family:sans-serif;
}
.container{
width: 100%;
height: 100vh;
background: linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.6)),url('./pexels-photo-346529.webp');
background-size: cover;
position: fixed;
background-position: center;
}
.navbar{
    width: 100%;
    margin: auto;
    padding: 0 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: relative;
}
h1{
    font-weight: bolder;
    cursor: pointer;
    text-decoration: none;
    color: white;
    padding-right: 150px;
}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
}
.navbar ul li a{
    text-decoration:none;
    color: white;
    font-weight: bolder;
}

.contant{
    width: 100%;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
}
.contant h3{
    margin-top: 80px;
    color:darkorange
}
.contant p{
    margin-top: 20px auto;
    line-height: 25px;
    color: white;
    row-gap: 4px;
}
@media screen and (max-width:600px)
{
    fieldset h1{
        font-size: 36px;
        line-height: 50px;
    }
}
    </style>
</head>
<body>
    <div class="container">
    <div class="navbar">
        <h1>😇 Welcome To My Protofolio </h1>
    <ul>
        <li> <a href="about.html">About</a></li>
        <li><a href="skills.html">Skills</a></li>
        <li><a href="projects.html">Project</a></li>
        <li> <a href="contact.html">Contact</a></li>
    </ul>
    </div>
    </div>
    <div class="contant">
        <h3>Introduction </h3>
        <p > Hi friends My self rajesh i'am pursuing <b>B Tech</b> in NVRT
        and this is my first website and check out my projects above, if you want  to suggest me, massage the contact on top
    </p>
    </div>
</body>
</html>

 
 
