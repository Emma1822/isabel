# isabel
Para isabel 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Para Isabel</title>

  <style>
    body{
      margin:0;
      font-family: 'Georgia', serif;
      background: linear-gradient(180deg,#0b0b0f,#1a1a25);
      color:#f2f2f2;
      text-align:center;
    }
    header{
      padding:40px 20px 20px;
      font-size:1.6em;
      letter-spacing:1px;
    }
    .intro{
      max-width:700px;
      margin:0 auto 30px;
      padding:0 20px;
      line-height:1.6;
      opacity:.95;
    }
    .gallery{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
      gap:20px;
      padding:20px;
      max-width:900px;
      margin:0 auto;
    }
    .card{
      background:#11131c;
      border-radius:14px;
      overflow:hidden;
      box-shadow:0 10px 25px rgba(0,0,0,.35);
    }
    .card img{
      width:100%;
      display:block;
    }
    .phrase{
      padding:14px;
      font-size:0.95em;
      opacity:.9;
    }
    footer{
      margin:40px 0 20px;
      font-size:0.9em;
      opacity:.8;
    }
    audio{
      margin-top:25px;
      width:90%;
      max-width:400px;
    }
  </style>
</head>

<body>

<header>
  Querida Isabel
</header>

<div class="intro">
  Me das tiempo, comprensión y cariño sin pedir nada a cambio.  
  Cambiaste mi forma de ver el amor, la compañía y el tiempo.  
  Después de estar solo, encontré en ti a alguien que no me juzga…  
  y eso lo cambió todo.
</div>

<!-- Música -->
<audio controls autoplay>
  <source src="audio/song.mp3" type="audio/mpeg">
  Tu navegador no soporta audio.
</audio>

<!-- Galería -->
<section class="gallery">

  <!-- FOTO 1 -->
  <div class="card">
    <img src="img/foto1.jpg" alt="Isabel 1">
    <div class="phrase">
      Llegaste sin prometer nada… y lo cambiaste todo.
    </div>
  </div>

  <!-- FOTO 2 -->
  <div class="card">
    <img src="img/foto2.jpg" alt="Isabel 2">
    <div class="phrase">
      Con solo estar, haces que todo se sienta en su lugar.
    </div>
  </div>

  <!-- FOTO 3 -->
  <div class="card">
    <img src="img/foto3.jpg" alt="Isabel 3">
    <div class="phrase">
      Tu forma de querer me enseñó a quedarme.
    </div>
  </div>

  <!-- FOTO 4 -->
  <div class="card">
    <img src="img/foto4.jpg" alt="Isabel 4">
    <div class="phrase">
      Aquella noche, bajo la luna, cuando me dijiste “te amo”.
    </div>
  </div>

</section>

<footer>
  Con amor,<br>
  <strong>Emmanuel Sanchez</strong>
</footer>

</body>
</html>
