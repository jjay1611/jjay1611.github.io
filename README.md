# jjstore.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>JJ Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }

    header {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }

    h1 {
      margin: 0;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 1.5rem;
    }

    .product {
      background: #fff;
      border-radius: 8px;
      padding: 1rem;
      width: 250px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    .product h3 {
      margin: 0.5rem 0;
    }

    .buy-btn {
      background: #222;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 1rem;
    }

    .buy-popup {
      display: none;
      background: #fff;
      border: 2px solid #ccc;
      padding: 1rem;
      margin-top: 1rem;
      border-radius: 6px;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: #fff;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>JJ Store</h1>
  <p>Affordable streetwear – Pay with Cash App</p>
</header>

<div class="products">
  <div class="product">
    <h3>Hoodies</h3>
    <p><strong>Price:</strong> $30</p>
    <p>Cozy and stylish.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Shirts</h3>
    <p><strong>Price:</strong> $15</p>
    <p>Casual wear for everyday use.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Long Sleeve Shirts</h3>
    <p><strong>Price:</strong> $15</p>
    <p>Comfortable and versatile.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Sweatpants</h3>
    <p><strong>Price:</strong> $30</p>
    <p>Relaxed fit for everyday comfort.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Shorts</h3>
    <p><strong>Price:</strong> $20</p>
    <p>Perfect for summer days.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <h3>Shoes</h3>
    <p><strong>Price:</strong> $150</p>
    <p>Any shoes you want.</p>
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

