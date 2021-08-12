<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>My Portfolio</title>
 <style>
 * {
  text-decoration: none;
}

body {
background-color: #f3f3f3;
}
header {
background-color: white;
width: 100%;
height: 100px;
}
header .header-brand {
font-size: 24px;
font-weight: 100px;
color: #111;
text-transform: uppercase;
display: block;
margin: 0 auto;
text-align: center;
padding: 20px 0;
}
header nav ul {
display: block;
margin: 0 auto;
width: fit-content;
text-transform: none;
}
header nav ul li {
display: inline-block;
list-style: none;
padding: 0 10px;
text-align: center;
}
header nav ul li a {
font-size: 18px;
font-weight: 1000px;
color: #111;
}
header .header-cases {
display: none;
}

.index-banner {
width: 100%;
height: calc(100vh - 100px);
background-image: url(./namnso-ukpanah-6UqJTfoXIq8-unsplash.jpg);
background-repeat: no-repeat;
background-position: center;
background-size: cover;
display: table;
}

.vertical-center {
display: table-cell;
}

.index-banner h2 {
color: white;
text-transform: uppercase;
text-align: center;
line-height: 60px;
font-size: 60px;
text-shadow: 2px 2px 8px #111;
}
.index-banner h1 {
font-size: 28px;
line-height: 40px;
color: #f3f3f3;
text-align: center;
text-shadow: 2px 2px 8px #111;
}
</style>

</head>
<body>
 <header>
   <a href="index.html" class="header-brand">Db_Expression</a>
   <nav>
    <ul>
     <li><a href="#">Portfolio</a></li>
     <li><a href="#">About me</a></li>
     <li><a href="#">Contact</a></li>
    </ul>
    <a href="#" class="header-cases">Cases</a>
   </nav>
 </header>
 <main>
   <section class="index-banner">
   <div class="vertical-center">
    <h2>I am a freelance<br>web developer</h2>
    <h1>With speciality in html, css and javascript</h1>
   </div>
    
   </section>
 </main>
 <footer>

 </footer>
</body>
</html>
