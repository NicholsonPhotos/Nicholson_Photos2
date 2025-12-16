<!DOCTYPE html>
<!-- ============================= -->
<!--  FILE 1: index.html (HOME)  -->
<!-- ============================= -->
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alexander Photography</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400&display=swap" rel="stylesheet">
  <style>
    body { margin:0; background:#0b0b0b; color:#eaeaea; font-family:Inter,sans-serif; }
    header { height:100vh; background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.9)), url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee'); background-size:cover; background-position:center; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; }
    h1 { font-family:'Playfair Display',serif; font-size:3.5rem; letter-spacing:3px; }
    nav { position:fixed; top:0; width:100%; padding:1rem; display:flex; justify-content:center; gap:2rem; background:rgba(0,0,0,.6); backdrop-filter: blur(6px); }
    nav a { color:#eaeaea; text-decoration:none; font-weight:300; letter-spacing:1px; }
    nav a:hover { color:#caa86a; }
    .section { padding:4rem 2rem; max-width:1100px; margin:auto; }
    .cards { display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:2rem; }
    .card { background:#111; border-radius:12px; overflow:hidden; }
    .card img { width:100%; height:300px; object-fit:cover; filter:grayscale(20%); }
    .card div { padding:1.5rem; }
    footer { padding:2rem; text-align:center; color:#777; }
  </style>
</head>
<body>
<nav>
  <a href="index.html">Home</a>
  <a href="sports.html">Sports</a>
  <a href="portraits.html">Portraits</a>
</nav>
<header>
  <h1>ALEXANDER</h1>
  <p>Cinematic • Sports • Portraits</p>
</header>
<section class="section">
  <h2>Portfolio</h2>
  <div class="cards">
    <a class="card" href="sports.html">
      <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b" />
      <div><h3>Sports</h3><p>Motion, intensity, raw emotion.</p></div>
    </a>
    <a class="card" href="portraits.html">
      <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" />
      <div><h3>Portraits</h3><p>Cinematic lighting and character.</p></div>
    </a>
  </div>
</section>
<footer>© 2025 Alexander Photography</footer>
</body>
</html>


<!-- ================================ -->
<!--  FILE 2: sports.html (SPORTS)  -->
<!-- ================================ -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sports | Alexander Photography</title>
  <style>
    body{margin:0;background:#0b0b0b;color:#eaeaea;font-family:Inter,sans-serif;}
    nav{padding:1rem;text-align:center;background:#000;}
    nav a{color:#eaeaea;text-decoration:none;margin:0 1rem;}
    h1{text-align:center;padding:2rem;font-family:'Playfair Display',serif;}
    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1rem;padding:2rem;}
    .gallery img{width:100%;height:350px;object-fit:cover;filter:contrast(110%) brightness(85%);} 
  </style>
</head>
<body>
<nav>
  <a href="index.html">Home</a>
  <a href="portraits.html">Portraits</a>
</nav>
<h1>Sports</h1>
<div class="gallery">
  <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b" />
  <img src="https://images.unsplash.com/photo-1521412644187-c49fa049e84d" />
  <img src="https://images.unsplash.com/photo-1508609349937-5ec4ae374ebf" />
</div>
</body>
</html>


<!-- =================================== -->
<!--  FILE 3: portraits.html (PORTRAITS) -->
<!-- =================================== -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portraits | Alexander Photography</title>
  <style>
    body{margin:0;background:#0b0b0b;color:#eaeaea;font-family:Inter,sans-serif;}
    nav{padding:1rem;text-align:center;background:#000;}
    nav a{color:#eaeaea;text-decoration:none;margin:0 1rem;}
    h1{text-align:center;padding:2rem;font-family:'Playfair Display',serif;}
    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1rem;padding:2rem;}
    .gallery img{width:100%;height:350px;object-fit:cover;filter:grayscale(20%) contrast(110%);} 
  </style>
</head>
<body>
<nav>
  <a href="index.html">Home</a>
  <a href="sports.html">Sports</a>
</nav>
<h1>Portraits</h1>
<div class="gallery">
  <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" />
  <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e" />
  <img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d" />
</div>
</body>
</html>
