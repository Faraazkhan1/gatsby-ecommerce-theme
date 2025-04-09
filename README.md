<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hijab Hub Kashmir</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Roboto', sans-serif; color: #333; background-color: #fdfcfb; }
    header {
      background: url('https://images.unsplash.com/photo-1603252110486-d2e5f0f5026c') no-repeat center center/cover;
      height: 100vh;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 4rem;
      background: rgba(0, 0, 0, 0.5);
      padding: 20px;
      border-radius: 10px;
    }
    header p {
      font-size: 1.3rem;
      margin-top: 15px;
      background: rgba(0, 0, 0, 0.3);
      padding: 10px 20px;
      border-radius: 8px;
    }
    .btn {
      margin-top: 25px;
      padding: 12px 30px;
      font-size: 1rem;
      background-color: #d4af37;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .btn:hover {
      background-color: #b48b19;
    }
    nav {
      position: absolute;
      top: 20px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 30px;
      background: rgba(255, 255, 255, 0.8);
      padding: 10px 20px;
      border-radius: 30px;
      font-weight: bold;
    }
    nav a {
      color: #333;
      text-decoration: none;
    }
    .products {
      padding: 50px 20px;
      text-align: center;
    }
    .products h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      margin-bottom: 30px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .product {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 20px;
      transition: transform 0.3s;
    }
    .product:hover {
      transform: translateY(-5px);
    }
    .product img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }
    .about, .contact {
      padding: 50px 20px;
      background: #f8f7f3;
      text-align: center;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#">Home</a>
    <a href="#products">Shop</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  <header>
    <h1>Hijab Hub Kashmir</h1>
    <p>Grace in every thread — Explore premium stoles & hijabs</p>
    <button class="btn">Shop Now</button>
  </header>
  <section class="products" id="products">
    <h2>Our Collection</h2>
    <div class="grid">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1618912539022-d21929e4ed46" alt="Stole 1">
        <h3>Silk Stole</h3>
        <p>Rs. 799</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1612178991384-2fd1e9f7d1e1" alt="Stole 2">
        <h3>Embroidered Hijab</h3>
        <p>Rs. 999</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1522336572468-97b06e8ef143" alt="Stole 3">
        <h3>Georgette Stole</h3>
        <p>Rs. 599</p>
      </div>
    </div>
  </section>
  <section class="about" id="about">
    <h2>About Us</h2>
    <p>Hijab Hub Kashmir brings you the finest collection of modest fashion, crafted with elegance and rooted in tradition. Every piece tells a story of grace and identity.</p>
  </section>
  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Have a question or want to place an order? Reach out at <strong>hijabhubkashmir@example.com</strong></p>
  </section>
  <footer>
    &copy; 2025 Hijab Hub Kashmir. All rights reserved.
  </footer>
</body>
</html>
