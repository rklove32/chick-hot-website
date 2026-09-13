# chick-hot-website
official website for chick hot-theni


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CHICK HOT | Theni</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:Arial, sans-serif;
    background:#080808;
    color:white;
}

header{
    position:sticky;
    top:0;
    z-index:1000;
    background:#050505;
    border-bottom:2px solid #e60000;
    padding:15px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:30px;
    font-weight:900;
}

.logo .red{
    color:#ff1616;
}

.logo .yellow{
    color:#ffd400;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-weight:bold;
}

nav a:hover{
    color:#ffd400;
}

.hero{
    min-height:90vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:50px 20px;

    background:
    radial-gradient(circle at 50% 40%,#8b0000 0%,#300000 25%,#080808 70%);
}

.badge{
    display:inline-block;
    background:#e60000;
    padding:10px 20px;
    border-radius:30px;
    font-weight:bold;
    margin-bottom:20px;
}

.hero h1{
    font-size:clamp(55px,10vw,110px);
    font-weight:1000;
    line-height:.9;
    text-transform:uppercase;
}

.hero h1 span{
    color:#ffd400;
}

.hero h2{
    margin-top:25px;
    font-size:24px;
    letter-spacing:5px;
}

.hero p{
    margin:20px auto;
    color:#ddd;
    font-size:18px;
    max-width:600px;
}

.btn{
    display:inline-block;
    padding:15px 28px;
    margin:8px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

.yellow-btn{
    background:#ffd400;
    color:#000;
}

.red-btn{
    background:#e60000;
    color:white;
}

.btn:hover{
    transform:translateY(-4px);
}

section{
    padding:80px 7%;
}

.title{
    text-align:center;
    font-size:45px;
    margin-bottom:45px;
}

.title span{
    color:#ffd400;
}

.menu{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:22px;
}

.card{
    background:#121212;
    border:1px solid #3a0000;
    border-radius:18px;
    padding:28px 20px;
    text-align:center;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
    border-color:#ff0000;
    box-shadow:0 10px 30px #300000;
}

.food-icon{
    font-size:55px;
    margin-bottom:15px;
}

.card h3{
    min-height:50px;
    font-size:18px;
}

.card p{
    color:#aaa;
    margin:8px;
}

.price{
    display:inline-block;
    background:#ffd400;
    color:#000 !important;
    padding:8px 18px;
    border-radius:20px;
    font-size:20px;
    font-weight:bold;
}

.why{
    background:#ffd400;
    color:#000;
}

.why .title span{
    color:#e60000;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    text-align:center;
    gap:25px;
}

.feature{
    padding:20px;
}

.feature-icon{
    font-size:45px;
    margin-bottom:10px;
}

.about{
    max-width:850px;
    margin:auto;
    text-align:center;
    line-height:1.8;
    color:#ddd;
    font-size:18px;
}

.location{
    text-align:center;
    background:#111;
}

.contact-box{
    max-width:600px;
    margin:auto;
    text-align:center;
    padding:35px;
    border:1px solid #e60000;
    border-radius:20px;
    background:#080808;
}

.contact-box p{
    margin:15px;
    font-size:18px;
}

footer{
    background:#030303;
    text-align:center;
    padding:40px 20px;
    border-top:2px solid #e60000;
}

footer .brand{
    font-size:28px;
    font-weight:bold;
}

footer .brand span{
    color:#ffd400;
}

@media(max-width:700px){

    header{
        flex-direction:column;
        gap:15px;
    }

    nav a{
        margin:5px;
        font-size:13px;
    }

    section{
        padding:60px 5%;
    }

    .hero{
        min-height:80vh;
    }

}

</style>
</head>

<body>

<header>

<div class="logo">
    <span class="red">CHICK</span>
    <span class="yellow"> HOT</span> 🍗
</div>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#location">Contact</a>
</nav>

</header>


<!-- HERO -->

<section class="hero" id="home">

<div>

    <div class="badge">🔥 WELCOME TO CHICK HOT</div>

    <h1>
        CHICK <span>HOT</span>
    </h1>

    <h2>
        SPICY • CRISPY • IRRESISTIBLE
    </h2>

    <p>
        Real chicken. Real spice.
        Unforgettable taste.
    </p>

    <a href="#menu" class="btn yellow-btn">
        🍗 VIEW MENU
    </a>

    <a href="#location" class="btn red-btn">
        📍 FIND US
    </a>

</div>

</section>


<!-- MENU -->

<section id="menu">

<h2 class="title">
    OUR <span>MENU</span>
</h2>

<div class="menu">

<div class="card">
    <div class="food-icon">🍗</div>
    <h3>ICONIC POPCORN CHICKEN</h3>
    <p class="price">₹30</p>
</div>

<div class="card">
    <div class="food-icon">🍗</div>
    <h3>FRIED CHICKEN "WONG'S"</h3>
    <p>2 Pieces</p>
    <p class="price">₹69</p>
</div>

<div class="card">
    <div class="food-icon">🍗</div>
    <h3>FRIED CHICKEN LEG PIECES</h3>
    <p>2 Pieces</p>
    <p class="price">₹89</p>
</div>

<div class="card">
    <div class="food-icon">🍗</div>
    <h3>FRIED CHICKEN LOLLIPOP</h3>
    <p>4 Pieces</p>
    <p class="price">₹89</p>
</div>

<div class="card">
    <div class="food-icon">🍔</div>
    <h3>FRIED CHICKEN BURGER</h3>
    <p class="price">₹89</p>
</div>

<div class="card">
    <div class="food-icon">🌯</div>
    <h3>FRIED CHICKEN ROLL</h3>
    <p class="price">₹99</p>
</div>

<div class="card">
    <div class="food-icon">🌯</div>
    <h3>CHICK HOT SPECIAL CHICKEN MIXTURE ROLL</h3>
    <p class="price">₹89</p>
</div>

</div>

</section>


<!-- WHY CHICK HOT -->

<section class="why">

<h2 class="title">
    WHY <span>CHICK HOT?</span>
</h2>

<div class="features">

<div class="feature">
    <div class="feature-icon">🍗</div>
    <h3>FRESH CHICKEN</h3>
</div>

<div class="feature">
    <div class="feature-icon">🔥</div>
    <h3>AUTHENTIC SPICE</h3>
</div>

<div class="feature">
    <div class="feature-icon">🛡️</div>
    <h3>HYGIENIC</h3>
</div>

<div class="feature">
    <div class="feature-icon">⭐</div>
    <h3>GREAT VALUE</h3>
</div>

</div>

</section>


<!-- ABOUT -->

<section id="about">

<h2 class="title">
    ABOUT <span>CHICK HOT</span>
</h2>

<div class="about">

<p>
CHICK HOT is a fried chicken spot in Theni,
serving hot, crispy and flavourful chicken.
</p>

<br>

<p>
Our mission is simple:
<strong>great food, great taste and great value.</strong>
</p>

<br>

<p>
🔥 SPICY &nbsp; • &nbsp; 🍗 CRISPY &nbsp; • &nbsp; ❤️ MADE FOR FOOD LOVERS
</p>

</div>

</section>


<!-- LOCATION -->

<section class="location" id="location">

<h2 class="title">
    FIND <span>CHICK HOT</span>
</h2>

<div class="contact-box">

<p>📍 <strong>Theni, Tamil Nadu</strong></p>

<p>📮 PIN: 625531</p>

<p>🕐 Open Daily</p>

<a
href="https://www.google.com/maps/search/?api=1&query=Theni,Tamil+Nadu"
target="_blank"
class="btn red-btn">

📍 GET DIRECTIONS

</a>

<br>

<a
href="https://wa.me/"
target="_blank"
class="btn yellow-btn">

💬 ORDER ON WHATSAPP

</a>

</div>

</section>


<!-- FOOTER -->

<footer>

<div class="brand">
    <span>CHICK</span> HOT 🍗
</div>

<br>

<p>
SPICY • CRISPY • IRRESISTIBLE
</p>

<br>

<p>
© 2026 CHICK HOT • Theni, Tamil Nadu
</p>

</footer>

</body>
</html>
