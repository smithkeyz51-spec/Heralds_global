# Heralds_global
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>The Heralds</title>

<style>

/* RESET */
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: Arial, sans-serif;
}

/* BODY */
body{
background:#0b0b0b;
color:white;
}

/* HEADER */
header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
background:#000;
}

.logo{
display:flex;
align-items:center;
gap:10px;
}

.logo img{
height:45px;
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500;
}

/* HERO */
.hero{
text-align:center;
padding:120px 20px;
background:linear-gradient(to bottom,#000,#111);
}

.hero h1{
font-size:42px;
margin-bottom:20px;
}

.hero p{
max-width:600px;
margin:auto;
opacity:0.8;
}

/* SECTION */
section{
padding:80px 20px;
max-width:1100px;
margin:auto;
}

h2{
text-align:center;
margin-bottom:40px;
font-size:30px;
}

/* SERVICES */
.services{
display:flex;
flex-wrap:wrap;
gap:20px;
justify-content:center;
}

.service{
background:#111;
padding:25px;
width:260px;
border-radius:10px;
border:1px solid #222;
}

/* PACKAGES (3D BOX STYLE) */
.packages{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:40px;
perspective:1000px;
}

.package{
width:260px;
height:360px;
position:relative;
transform-style:preserve-3d;
transition:0.5s;
cursor:pointer;
}

.package:hover{
transform:rotateY(10deg) rotateX(5deg) scale(1.05);
}

/* FRONT FACE */
.package .box{
position:absolute;
width:100%;
height:100%;
border-radius:15px;
padding:25px;
display:flex;
flex-direction:column;
justify-content:space-between;
box-shadow:0 20px 40px rgba(0,0,0,0.5);
}

/* STYLES */
.sniper{
background:#111;
border:1px solid #333;
}

.eagle{
background:linear-gradient(135deg,#d4af37,#8c6b1f);
color:black;
}

.mona{
background:#f3e7c7;
color:black;
}

/* TEXT */
.package h3{
text-align:center;
margin-bottom:10px;
}

.package p{
font-size:14px;
text-align:center;
margin-bottom:10px;
}

.package ul{
font-size:13px;
padding-left:18px;
}

.price{
text-align:center;
font-weight:bold;
margin-top:10px;
}

/* SOCIAL */
.social{
text-align:center;
}

.social a{
display:inline-block;
margin:10px;
padding:10px 20px;
background:white;
color:black;
text-decoration:none;
border-radius:5px;
}

/* FOOTER */
footer{
text-align:center;
padding:30px;
background:#000;
margin-top:50px;
}

</style>

</head>

<body>

<!-- HEADER -->
<header>
<div class="logo">
<img src="images/logo.png">
<h2>The Heralds</h2>
</div>

<nav>
<a href="#">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#packages">Packages</a>
<a href="#social">Social</a>
</nav>
</header>

<!-- HERO -->
<section class="hero">
<h1>We Build Powerful Digital Brands</h1>
<p>Transforming visibility into authority, attention into demand, and brands into market leaders.</p>
</section>

<!-- ABOUT -->
<section id="about">
<h2>About</h2>
<p style="text-align:center; max-width:700px; margin:auto;">
The Heralds is a premium brand growth agency focused on turning businesses into dominant digital forces through strategy, content, and community.
</p>
</section>

<!-- SERVICES -->
<section id="services">
<h2>Services</h2>

<div class="services">

<div class="service">Social Media Strategy</div>
<div class="service">Content Creation</div>
<div class="service">Brand Identity</div>
<div class="service">Paid Advertising</div>
<div class="service">Community Growth</div>
<div class="service">Analytics & Insights</div>

</div>

</section>

<!-- PACKAGES -->
<section id="packages">

<h2>Premium Brand Domination Packages</h2>

<div class="packages">

<div class="package">
<div class="box sniper">
<h3>SNIPER</h3>
<p>Precision. Speed. Results.</p>
<ul>
<li>12 high-impact HD Brand Videos</li>
<li>Scroll-stopping edits with persuasive High-converting captions</li>
<li>Professional cinematic color grading</li>
<li>Strategic brand audit + growth blueprint</li>
<li>Conversion-driven content calender with authentic powerful CTAs</li>
</ul>
<div class="price">₦199,900</div>
</div>
</div>

<div class="package">
<div class="box eagle">
<h3>EAGLE</h3>
<p>Scale Faster. Sell Smarter.</p>
<ul>
<li>16 Premium HD brand Videos</li>
<li>Hard-hitting edits with compelling, sales-driven captions</li>
<li>Elite cinematic color grading</li>
<li>Brand strategy</li>
<li>Customizable Meta Ads plan engineered to sky rocket sales</li>
</ul>
<div class="price">₦299,900</div>
</div>
</div>

<div class="package">
<div class="box mona">
<h3>MONA LISA</h3>
<p>Total Authority.</p>
<ul>
<li>20 cinematic, ultra-Premium brand Videos</li>
<li>High-converting, luxury edits with elite level captions</li>
<li>Elite color grading + high end production quality</li>
<li>ROI-focused, full form Meta Ads ecosystem</li>
<li>1-on-1 consulting</li>
<li>24/7 Social media management</li>
</ul>
<div class="price">₦499,900</div>
</div>
</div>

</div>

</section>

<!-- SOCIAL -->
<section id="social">

<h2>Connect With Us</h2>

<div class="social">
<a href="https://instagram.com/heralds_global">Instagram</a>
<a href="https://x.com/pkenecrypt">X</a>
<a href="mailto:edwardwilfred17@gmail.com">email</a>
</div>

</section>

<!-- FOOTER -->
<footer>
<p>The Heralds</p>
<p>We build brands into dominant digital forces.</p>
<p>© 2026 The Heralds. All rights reserved.</p>
</footer>

</body>
</html>
