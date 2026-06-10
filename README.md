<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ali Amiri | Portfolio</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,sans-serif;
}

body{
background:#050816;
color:white;
overflow-x:hidden;
}

/* Stars */
.stars{
position:fixed;
width:100%;
height:100%;
top:0;
left:0;
background:url("https://www.transparenttextures.com/patterns/stardust.png");
animation:moveStars 80s linear infinite;
z-index:-2;
}

@keyframes moveStars{
from{transform:translateY(0);}
to{transform:translateY(-1000px);}
}

/* Matrix */
.matrix{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
opacity:.08;
z-index:-1;
background-image:
linear-gradient(rgba(0,255,0,.4) 1px, transparent 1px);
background-size:100% 25px;
}

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

h1{
font-size:70px;
background:linear-gradient(90deg,#00ffff,#8a2be2);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.subtitle{
margin-top:15px;
font-size:22px;
color:#ccc;
}

.icons{
margin-top:25px;
display:flex;
gap:20px;
font-size:35px;
}

.icons i{
transition:.3s;
}

.icons i:hover{
transform:scale(1.2);
color:#00ffff;
}

section{
max-width:1000px;
margin:auto;
padding:80px 20px;
}

.card{
background:rgba(255,255,255,.05);
backdrop-filter:blur(8px);
border:1px solid rgba(255,255,255,.1);
padding:25px;
border-radius:20px;
margin-bottom:25px;
}

.card h2{
margin-bottom:15px;
color:#00ffff;
}

.skills{
display:flex;
flex-wrap:wrap;
gap:10px;
}

.skill{
padding:10px 15px;
background:#10172d;
border-radius:12px;
}

.contact a{
display:block;
margin-top:10px;
color:white;
text-decoration:none;
}

footer{
text-align:center;
padding:40px;
color:#888;
}
</style>
</head>

<body>

<div class="stars"></div>
<div class="matrix"></div>

<header>

<h1>ALI AMIRI</h1>

<p class="subtitle">
🚀 Programmer • Gamer • Tech Enthusiast
</p>

<div class="icons">
<i class="fas fa-code"></i>
<i class="fas fa-gamepad"></i>
<i class="fas fa-microchip"></i>
<i class="fas fa-robot"></i>
</div>

</header>

<section>

<div class="card">
<h2>👨‍💻 About Me</h2>

<p>
سلام، من علی امیری هستم.
به برنامه‌نویسی، تکنولوژی، طراحی وب، گیم و یادگیری چیزهای جدید علاقه دارم.
در حال یادگیری توسعه وب و ساخت پروژه‌های حرفه‌ای هستم و هدفم تبدیل شدن به یک توسعه‌دهنده حرفه‌ای است.
</p>

</div>

<div class="card">
<h2>⚡ Skills</h2>

<div class="skills">
<div class="skill">HTML</div>
<div class="skill">CSS</div>
<div class="skill">JavaScript</div>
<div class="skill">GitHub</div>
<div class="skill">Technology</div>
<div class="skill">Gaming</div>
</div>

</div>

<div class="card">
<h2>🎯 Interests</h2>

<p>
💻 Programming<br>
🎮 Gaming<br>
🤖 Artificial Intelligence<br>
🌌 Space & Technology<br>
🚀 Web Development
</p>

</div>

<div class="card contact">
<h2>📬 Contact Me</h2>

<a href="mailto:Aliamirishirani4@gmail.com">
📧 Aliamirishirani4@gmail.com
</a>

<a href="https://instagram.com/Ali.amiri.shirani">
📸 @Ali.amiri.shirani
</a>

</div>

</section>

<footer>

© 2026 Ali Amiri | Built with ❤️ and Code

</footer>

</body>
</html>