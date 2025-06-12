# jjstore.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>JJ Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff6f0;
      color: #330a00;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #e94e1b; /* bright orange/red from logo */
      color: white;
      padding: 20px;
      text-align: center;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
    }
    header img {
      height: 50px;
      width: auto;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
      font-weight: 700;
      text-shadow: 1px 1px 2px #330a00;
    }
    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }
    .product {
      background: #fff;
      border: 2px solid #e94e1b;
      border-radius: 12px;
      padding: 15px;
      box-shadow: 3px 3px 8px rgba(233, 78, 27, 0.4);
      text-align: center;
      transition: transform 0.2s ease;
    }
    .product:hover {
      transform: scale(1.05);
      box-shadow: 5px 5px 15px rgba(233, 78, 27, 0.6);
    }
    .product img {
      max-width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 12px;
    }
    .product h3 {
      margin: 10px 0 6px;
      color: #b73200;
    }
    .product p {
      margin: 6px 0;
      color: #552100;
    }
    .buy-btn {
      background-color: #e94e1b;
      border: none;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1em;
      transition: background-color 0.3s ease;
    }
    .buy-btn:hover {
      background-color: #b73200;
    }
    .buy-popup {
      display: none;
      margin-top: 10px;
      background: #ffefde;
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #e94e1b;
      color: #b73200;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.imgur.com/PlwHCu0.png" alt="JJ Store Logo" />
    <h1>JJ Store</h1>
  </header>

  <div class="container">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1520975693417-c1b21ff9a28a?auto=format&fit=crop&w=600&q=80" alt="Hoodie" />
      <h3>Hoodies</h3>
      <p><strong>Price:</strong> $40</p>
      <p>Cozy and stylish.</p>
      <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
      <div class="buy-popup">
        <p><strong>Cash App:</strong> $jamesjay1611</p>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1520975701442-7a51f3c32053?auto=format&fit=crop&w=600&q=80" alt="Shirt" />
      <h3>Shirts</h3>
      <p><strong>Price:</strong> $25</p>
      <p>Casual wear for everyday use.</p>
      <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
      <div class="buy-popup">
        <p><strong>Cash App:</strong> $jamesjay1611</p>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1520975709831-f57d44bd36ec?auto=format&fit=crop&w=600&q=80" alt="Long Sleeve Shirt" />
      <h3>Long Sleeve Shirts</h3>
      <p><strong>Price:</strong> $30</p>
      <p>Comfortable and versatile.</p>
      <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
      <div class="buy-popup">
        <p><strong>Cash App:</strong> $jamesjay1611</p>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1600185365670-b153d8ed35b6?auto=format&fit=crop&w=600&q=80" alt="Sweatpants" />
      <h3>Sweatpants</h3>
      <p><strong>Price:</strong> $35</p>
      <p>Relaxed fit for everyday comfort.</p>
      <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
      <div class="buy-popup">
        <p><strong>Cash App:</strong> $jamesjay1611</p>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&w=600&q=80" alt="Shorts" />
      <h3>Shorts</h3>
      <p><strong>Price:</strong> $20</p>
      <p>Perfect for summer days.</p>
      <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
      <div class="buy-popup">
        <p><strong>Cash App:</strong> $jamesjay1611</p>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=600&q=80" alt="Shoes" />
      <h3>Shoes</h3>
      <p><strong>Price:</strong> $50</p>
      <p>Fresh kicks for any occasion.</p>
      <button class="buy-btn" onclick="togglePopup(this)">Buy Now</button>
      <div class="buy-popup">
        <p><strong>Cash App:</strong> $jamesjay1611</p>
      </div>
    </div>
  </div>

  <script>
    function togglePopup(button) {
      const popup = button.nextElementSibling;
      if (popup.style.display === "block") {
        popup.style.display = "none";
      } else {
        popup.style.display = "block";
      }
    }
  </script>
</body>
</html>

