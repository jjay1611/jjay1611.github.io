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

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 6px;
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
    <img src="https://images.unsplash.com/photo-1618354691084-d7090f785b05?fit=crop&w=600&q=80" alt="Hoodie">
    <h3>Hoodies</h3>
    <p><strong>Price:</strong> $40</p>
    <p>Cozy and stylish.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1618354691193-3c9b48e75c3e?fit=crop&w=600&q=80" alt="Shirt">
    <h3>Shirts</h3>
    <p><strong>Price:</strong> $25</p>
    <p>Casual wear for everyday use.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1586118106073-75a99c1c4c9c?fit=crop&w=600&q=80" alt="Long Sleeve">
    <h3>Long Sleeve Shirts</h3>
    <p><strong>Price:</strong> $30</p>
    <p>Comfortable and versatile.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1620799140400-9cbbf5cf5bcf?fit=crop&w=600&q=80" alt="Sweatpants">
    <h3>Sweatpants</h3>
    <p><strong>Price:</strong> $35</p>
    <p>Relaxed fit for everyday comfort.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1598032898502-6d22d2a3e582?fit=crop&w=600&q=80" alt="Shorts">
    <h3>Shorts</h3>
    <p><strong>Price:</strong> $20</p>
    <p>Perfect for summer days.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?fit=crop&w=600&q=80" alt="Shoes">
    <h3>Shoes</h3>
    <p><strong>Price:</strong> $50</p>
    <p>Fresh kicks for any occasion.</p>
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
