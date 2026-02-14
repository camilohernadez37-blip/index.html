<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mi Universo 💖</title>

<style>
body{
    margin:0;
    overflow:hidden;
    background:black;
    font-family:Arial, sans-serif;
    color:white;
}

/* ESTRELLAS */
body::before{
    content:"";
    position:absolute;
    width:200%;
    height:200%;
    background-image: radial-gradient(white 1px, transparent 1px);
    background-size:70px 70px;
    animation: starsMove 90s linear infinite;
    opacity:0.3;
}
@keyframes starsMove{
    from{transform:translate(0,0);}
    to{transform:translate(-800px,-800px);}
}

/* CENTRO */
.center{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    text-align:center;
}

/* GALAXIA */
.galaxy{
    width:320px;
    height:320px;
    border-radius:50%;
    background: radial-gradient(circle, hotpink 0%, purple 50%, transparent 75%);
    position:absolute;
    top:-160px;
    left:-160px;
    animation: galaxySpin 30s linear infinite;
    box-shadow:0 0 80px hotpink;
}
@keyframes galaxySpin{
    from{transform:rotate(0deg);}
    to{transform:rotate(360deg);}
}

.characters{
    font-size:50px;
}

.title{
    font-size:30px;
    color:#ff66cc;
    text-shadow:0 0 25px hotpink;
    margin-top:10px;
}

/* ORBITA */
.orbit{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    animation: orbitSpin linear infinite;
}

@keyframes orbitSpin{
    from{transform:translate(-50%,-50%) rotate(0deg);}
    to{transform:translate(-50%,-50%) rotate(360deg);}
}

/* PLANETA */
.planet{
    position:absolute;
    top:0;
    left:50%;
    transform:translateX(-50%);
    width:120px;
    height:120px;
    border-radius:50%;
    background: radial-gradient(circle at 30% 30%, #ff99cc, #cc0066);
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:12px;
    font-size:13px;
    box-shadow:0 0 30px hotpink;
    animation: planetSpin 12s linear infinite;
}

/* ROTACIÓN DEL PLANETA SOBRE SÍ MISMO */
@keyframes planetSpin{
    from{transform:translateX(-50%) rotate(0deg);}
    to{transform:translateX(-50%) rotate(-360deg);}
}
</style>
</head>

<body>

<div class="center">
    <div class="galaxy"></div>
    <div class="characters">🐱 🧸🐻 💕</div>
    <div class="title">Te amo mi princesa 💖</div>
</div>

<!-- PLANETAS -->

<div class="orbit" style="width:400px;height:400px;animation-duration:25s;">
    <div class="planet">Eres lo mejor</div>
</div>

<div class="orbit" style="width:550px;height:550px;animation-duration:30s;">
    <div class="planet">Mi amor eterno</div>
</div>

<div class="orbit" style="width:700px;height:700px;animation-duration:35s;">
    <div class="planet">Eres mi universo</div>
</div>

<div class="orbit" style="width:850px;height:850px;animation-duration:40s;">
    <div class="planet">Mi corazón es tuyo</div>
</div>

<div class="orbit" style="width:1000px;height:1000px;animation-duration:45s;">
    <div class="planet">Siempre contigo</div>
</div>

<div class="orbit" style="width:1150px;height:1150px;animation-duration:50s;">
    <div class="planet">Mi felicidad eres tú</div>
</div>

<div class="orbit" style="width:1300px;height:1300px;animation-duration:55s;">
    <div class="planet">Mi princesa hermosa</div>
</div>

<div class="orbit" style="width:1450px;height:1450px;animation-duration:60s;">
    <div class="planet">Te amo infinitamente</div>
</div>

<div class="orbit" style="width:1600px;height:1600px;animation-duration:65s;">
    <div class="planet">Eres mi destino</div>
</div>

<div class="orbit" style="width:1750px;height:1750px;animation-duration:70s;">
    <div class="planet">Mi estrella brillante</div>
</div>

</body>
</html>
