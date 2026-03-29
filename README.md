<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Le Scent</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #f8f8f8, #eaeaea);
      margin: 0;
      text-align: center;
    }

    header {
      background: black;
      color: white;
      padding: 25px;
      font-size: 30px;
      letter-spacing: 3px;
      animation: fadeIn 1.5s ease;
    }

    .container {
      padding: 20px;
    }

    .product {
      background: white;
      margin: 20px auto;
      padding: 20px;
      border-radius: 15px;
      width: 80%;
      max-width: 400px;
      box-shadow: 0px 5px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      animation: fadeUp 1s ease;
    }

    .product:hover {
      transform: scale(1.05);
      box-shadow: 0px 10px 25px rgba(0,0,0,0.2);
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background: black;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s, transform 0.2s;
    }

    .btn:hover {
      background: #333;
      transform: translateY(-2px);
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

  </style>
</head>

<body>

<header>LE SCENT</header>

<div class="container">
  <h2>Perfumes originales ✨</h2>

  <div class="product">
    <h3>Dior Sauvage</h3>
    <p>$...</p>
    <a class="btn" href="https://wa.me/549XXXXXXXXXX">Comprar</a>
  </div>

  <div class="product">
    <h3>Carolina Herrera 212</h3>
    <p>$...</p>
    <a class="btn" href="https://wa.me/549XXXXXXXXXX">Comprar</a>
  </div>

  <h3>Contacto</h3>
  <p>Instagram: @tuusuario</p>
</div>

</body>
</html>
