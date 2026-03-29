<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Le Scent</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }

    header {
      background: black;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 28px;
      letter-spacing: 3px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      border-radius: 10px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    .price {
      font-weight: bold;
      margin: 10px 0;
    }

    .btn {
      display: inline-block;
      padding: 10px;
      background: black;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    .btn:hover {
      background: #333;
    }
  </style>
</head>
<body>

<header>LE SCENT</header>

<div class="grid">

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Perfume">
    <h3>Dior Sauvage</h3>
    <p class="price">$120.000</p>
    <a class="btn" href="https://wa.me/549XXXXXXXXXX?text=Hola%20quiero%20comprar%20Dior%20Sauvage">Comprar</a>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Perfume">
    <h3>Carolina Herrera 212</h3>
    <p class="price">$95.000</p>
    <a class="btn" href="https://wa.me/549XXXXXXXXXX?text=Hola%20quiero%20comprar%20212">Comprar</a>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="Perfume">
    <h3>Invictus</h3>
    <p class="price">$110.000</p>
    <a class="btn" href="https://wa.me/549XXXXXXXXXX?text=Hola%20quiero%20comprar%20Invictus">Comprar</a>
  </div>

</div>

</body>
</html>
</html>
