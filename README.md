# steve-abby
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Maya’s Cats 🐾</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: linear-gradient(to bottom, #f7f2ff, #ffffff);
      text-align: center;
    }

    header {
      background-color: #6a5acd;
      color: white;
      padding: 1.5rem;
    }

    h1 {
      margin: 0;
      font-size: 2rem;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      border-radius: 15px;
      padding: 15px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.1);
    }

    .card img {
      width: 100%;
      border-radius: 12px;
      height: 250px;
      object-fit: cover;
    }

    .name {
      font-size: 1.4rem;
      margin-top: 10px;
      font-weight: bold;
      color: #444;
    }

    .caption {
      font-size: 0.95rem;
      color: #777;
      margin-top: 5px;
    }

    footer {
      margin: 20px;
      color: #777;
    }
  </style>
</head>

<body>

<header>
  <h1>🐱 Maya and Phoebe's kids🐾</h1>
  <p>Tap again for more cuteness</p>
</header>

<section class="gallery">

  <!-- Abby -->
  <div class="card">
    <img src="abby.jpg" alt="Abby">
    <div class="name">Abby</div>
    <div class="caption">I’m from Pennsylvania 🏡</div>
  </div>

  <!-- Stevie -->
  <div class="card">
    <img src="stevie.jpg" alt="Stevie">
    <div class="name">Stevie</div>
    <div class="caption">I'm just a wittle baby</div>
  </div>

</section>

<footer>
  <p>Made with ❤️ for Abby (rip) & Stevie</p>
</footer>

</body>
</html>