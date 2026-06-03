<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Valhalla Global</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0b0b0b;
color:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:black;
border-bottom:1px solid #222;
}

.logo{
font-size:30px;
font-weight:bold;
color:#f4b400;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero h1{
font-size:60px;
color:#f4b400;
}

.hero p{
font-size:20px;
max-width:700px;
margin:20px 0;
}

.btn{
background:#f4b400;
color:black;
padding:15px 35px;
border:none;
border-radius:8px;
font-weight:bold;
text-decoration:none;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
padding:80px 10%;
}

.card{
background:#151515;
padding:25px;
border-radius:12px;
border:1px solid #222;
}

.card h3{
color:#f4b400;
margin-bottom:10px;
}

footer{
text-align:center;
padding:30px;
border-top:1px solid #222;
}
</style>

</head>
<body>

<header>
<div class="logo">VALHALLA GLOBAL</div>

<nav>
<a href="#">Home</a>
<a href="#">Marketplace</a>
<a href="#">Become Seller</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h1>VALHALLA GLOBAL</h1>

<p>
A verified seller marketplace where trusted traders connect with buyers worldwide.
</p>

<a href="#" class="btn">Become a Seller</a>
</section>

<section class="features">

<div class="card">
<h3>Verified Sellers</h3>
<p>Government ID and KYC verification required.</p>
</div>

<div class="card">
<h3>Secure Payments</h3>
<p>Protected transactions for buyers and sellers.</p>
</div>

<div class="card">
<h3>Global Reach</h3>
<p>Connect with customers around the world.</p>
</div>

<div class="card">
<h3>Fraud Detection</h3>
<p>Advanced systems help keep the platform safe.</p>
</div>

</section>

<footer>
© 2026 Valhalla Global. All Rights Reserved.
</footer>

</body>
</html># Valhalla-global-