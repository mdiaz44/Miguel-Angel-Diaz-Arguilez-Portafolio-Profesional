---
title: Datos BC
layout: null
---

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Datos BC</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{

height:100vh;

display:flex;

justify-content:center;

align-items:center;

background:
linear-gradient(rgba(4,30,66,.75),rgba(4,30,66,.75)),
url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1800&q=80");

background-size:cover;
background-position:center;

color:white;

}

.card{

width:90%;
max-width:650px;

background:rgba(255,255,255,.12);

backdrop-filter:blur(18px);

padding:55px;

border-radius:22px;

text-align:center;

box-shadow:0 15px 40px rgba(0,0,0,.35);

animation:fade 1s;

}

h1{

font-size:3rem;
margin-bottom:20px;
font-weight:700;

}

p{

font-size:1.15rem;
line-height:1.8;
margin-bottom:35px;
opacity:.95;

}

.btn{

display:inline-block;

padding:18px 40px;

background:#00A651;

color:white;

text-decoration:none;

font-size:20px;

font-weight:600;

border-radius:12px;

transition:.3s;

}

.btn:hover{

transform:translateY(-4px);
background:#008A44;

}

small{

display:block;
margin-top:30px;
opacity:.75;

}

@keyframes fade{

from{
opacity:0;
transform:translateY(20px);
}

to{
opacity:1;
transform:translateY(0);
}

}

</style>

</head>

<body>

<div class="card">

<h1>Datos BC</h1>

<p>
Plataforma para la consulta de información estadística oficial del Estado de Baja California.
</p>

<a class="btn"
href="https://www.ceieg.bajacalifornia.gob.mx/estadisticas-sectoriales/">
Entrar a Estadísticas Sectoriales
</a>

<small>
COPLADE • Gobierno del Estado de Baja California
</small>

</div>

</body>
</html>
