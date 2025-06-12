<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>JJ Store</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #fff;
      color: #000;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background: #fff;
      color: #000;
      text-align: center;
      padding: 1.5rem 1rem;
      border-bottom: 1px solid #000;
    }

    header h1 {
      margin: 0;
      font-weight: 900;
      letter-spacing: 2px;
    }

    header p {
      margin: 0.4rem 0 0;
      font-size: 1.1rem;
      font-style: italic;
      color: #000;
    }

    .products {
      flex-grow: 1;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 1.8rem;
    }

    .product {
      background: #fff;
      border-radius: 12px;
      padding: 1rem;
      width: 260px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.2s ease;
      border: 1px solid #000;
    }

    .product:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .product h3 {
      margin: 0 0 0.4rem 0;
      color: #000;
    }

    .product p {
      margin: 0.3rem 0;
      font-weight: 600;
      color: #000;
    }

    .buy-btn {
      background: #000;
      color: #fff;
      border: none;
      padding: 0.6rem 1.4rem;
      cursor: pointer;
      border-radius: 30px;
      font-weight: bold;
      margin-top: 1rem;
      box-shadow: none;
      transition: background-color 0.3s ease;
    }

    .buy-btn:hover {
      background: #333;
      color: #fff;
    }

    .buy-popup {
      display: none;
      background: #fff;
      border: 2px solid #000;
      padding: 1rem;
      margin-top: 1rem;
      border-radius: 10px;
      font-weight: bold;
      color: #000;
    }

    footer {
      background: #fff;
      color: #000;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      border-top: 1px solid #000;
      user-select: none;
    }
  </style>
</head>
<body>

<header>
  <h1>JJ Store</h1>
  <p>Affordable streetwear – Pay with Cash App</p>
  <p>Add me on snap for purchasing details-jamesjay1116</p>
</header>

<div class="products">

  <div class="product">
    <h3>Custom Made Hoodies</h3>
    <p><strong>Price:</strong> $35</p>
    <p>Cozy and stylish.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Custom Made Shirts</h3>
    <p><strong>Price:</strong> $20</p>
    <p>Casual wear for everyday use.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Custom Made Long Sleeve Shirts</h3>
    <p><strong>Price:</strong> $25</p>
    <p>Comfortable and versatile.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Custom Made Sweatpants</h3>
    <p><strong>Price:</strong> $30</p>
    <p>Relaxed fit for everyday comfort.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

</div>

<footer>
  &copy; 2025 JJ Store. All rights reserved.
</footer>

<script>
  function togglePopup(button) {
    const popup = button.nextElementSibling;
    popup.style.display = popup.style.display === "block" ? "none" : "block";
  }
</script>

</body>
</html>
