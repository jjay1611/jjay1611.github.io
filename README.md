# jjstore.github.io
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
      background: linear-gradient(135deg, #ffd89b, #19547b);
      color: #222;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background: #0f4c75;
      color: #fff;
      text-align: center;
      padding: 1.5rem 1rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
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
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      text-align: center;
      transition: transform 0.2s ease;
    }

    .product:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    }

    .product img {
      width: 100%;
      height: 190px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 1rem;
      box-shadow: 0 2px 8px rgba(15,76,117,0.3);
    }

    .product h3 {
      margin: 0 0 0.4rem 0;
      color: #0f4c75;
    }

    .product p {
      margin: 0.3rem 0;
      font-weight: 600;
    }

    .buy-btn {
      background: #f9a825;
      color: #111;
      border: none;
      padding: 0.6rem 1.4rem;
      cursor: pointer;
      border-radius: 30px;
      font-weight: bold;
      margin-top: 1rem;
      box-shadow: 0 4px 6px rgba(249,168,37,0.6);
      transition: background-color 0.3s ease;
    }

    .buy-btn:hover {
      background: #c17900;
      color: #fff;
    }

    .buy-popup {
      display: none;
      background: #fff8e1;
      border: 2px solid #f9a825;
      padding: 1rem;
      margin-top: 1rem;
      border-radius: 10px;
      font-weight: bold;
      color: #c17900;
    }

    footer {
      background: #0f4c75;
      color: #fff;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      box-shadow: 0 -4px 10px rgba(0,0,0,0.3);
      user-select: none;
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
    <img src="https://images.unsplash.com/photo-1618354691084-d7090f785b05?fit=crop&w=600&q=80" alt="Hoodie" />
    <h3>Hoodies</h3>
    <p><strong>Price:</strong> $40</p>
    <p>Cozy and stylish.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1618354691193-3c9b48e75c3e?fit=crop&w=600&q=80" alt="Shirt" />
    <h3>Shirts</h3>
    <p><strong>Price:</strong> $25</p>
    <p>Casual wear for everyday use.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1586118106073-75a99c1c4c9c?fit=crop&w=600&q=80" alt="Long Sleeve Shirt" />
    <h3>Long Sleeve Shirts</h3>
    <p><strong>Price:</strong> $30</p>
    <p>Comfortable and versatile.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1620799140400-9cbbf5cf5bcf?fit=crop&w=600&q=80" alt="Sweatpants" />
    <h3>Sweatpants</h3>
    <p><strong>Price:</strong> $35</p>
    <p>Relaxed fit for everyday comfort.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1598032898502-6d22d2a3e582?fit=crop&w=600&q=80" alt="Shorts" />
    <h3>Shorts</h3>
    <p><strong>Price:</strong> $20</p>
    <p>Perfect for summer days.</p>
    <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
    <div class="buy-popup">
      <p><strong>Cash App:</strong> $jamesjay1611</p>
    </div>
  </div>

  <div class="product">
    <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?fit=crop&w=600&q=80" alt="Shoes" />
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
