<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Kazi International</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#080808;
color:white;
overflow-x:hidden;
}

header{
position:fixed;
top:0;
width:100%;
padding:20px 40px;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(0,0,0,.45);
backdrop-filter:blur(12px);
z-index:999;
}

.logo{
font-size:30px;
font-weight:bold;
color:#d4af37;
letter-spacing:2px;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
transition:.3s;
}

nav a:hover{
color:#d4af37;
}

.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
url('https://images.unsplash.com/photo-1566073771259-6a8506099945?q=80&w=1600')
center/cover;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
animation:zoom 12s infinite alternate;
}

.hero h1{
font-size:65px;
color:#d4af37;
}

.hero p{
font-size:22px;
margin-top:15px;
}

.btn{
padding:14px 28px;
border:none;
border-radius:40px;
background:#d4af37;
color:black;
font-weight:bold;
margin-top:20px;
cursor:pointer;
transition:.3s;
}

.btn:hover{
transform:scale(1.1);
}

section{
padding:90px 20px;
}

.title{
text-align:center;
font-size:42px;
color:#d4af37;
margin-bottom:40px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
max-width:1200px;
margin:auto;
}

.card{
background:#141414;
border-radius:15px;
overflow:hidden;
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
max-width:1200px;
margin:auto;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
transition:.4s;
}

.gallery img:hover{
transform:scale(1.05);
}

.contact{
text-align:center;
}

footer{
padding:25px;
background:#111;
text-align:center;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
width:60px;
height:60px;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
font-size:28px;
text-decoration:none;
z-index:9999;
animation:float 2s infinite;
}

@keyframes zoom{
from{transform:scale(1);}
to{transform:scale(1.08);}
}

@keyframes float{
0%{transform:translateY(0);}
50%{transform:translateY(-8px);}
100%{transform:translateY(0);}
}

</style>
</head>

<body>

<header>

<div class="logo">KAZI INTERNATIONAL</div>

<nav>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Kazi International</h1>

<p>Luxury • Trust • Excellence</p>

<a href="tel:9535056953">
<button class="btn">Call Now</button>
</a>

</section>

<section id="services">

<h2 class="title">Our Services</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1455587734955-081b22074882?q=80&w=1200">
<div class="card-content">
<h3>Premium Hospitality</h3>
<p>Luxury guest experience with professional service.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1520250497591-112f2f40a3f4?q=80&w=1200">
<div class="card-content">
<h3>Luxury Stay</h3>
<p>Comfortable and elegant accommodation.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=1200">
<div class="card-content">
<h3>Fine Dining</h3>
<p>Premium food and restaurant experience.</p>
</div>
</div>

</div>

</section>

<section id="gallery">

<h2 class="title">Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1445019980597-93fa8acb246c?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1551882547-ff40c63fe5fa?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1520250497591-112f2f40a3f4?q=80&w=1200">

</div>

</section>

<section id="contact">

<h2 class="title">Contact Us</h2>

<div class="contact">

<p>📞 9535056953</p>

<p>📍 Mobile Network Available Across India</p>

<br>

<a href="tel:9535056953">
<button class="btn">Call Now</button>
</a>

<br><br>

<a href="https://wa.me/919535056953?text=Hello%20Kazi%20International" target="_blank">
<button class="btn">WhatsApp Us</button>
</a>

</div>

</section>

<footer>

© 2026 Kazi International

</footer>

<a href="https://wa.me/919535056953" class="whatsapp" target="_blank">

💬

</a>

</body>
</html>
