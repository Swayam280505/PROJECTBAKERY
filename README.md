<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home Bakery</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background-color: #1c1c1c;
      color: #f8e1dc;
    }
    header {
      background-color: #3e2c29;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-size: 1.8rem;
      color: #f6c1b4;
    }
    nav a {
      color: #f8e1dc;
      margin-left: 2rem;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      text-align: center;
      padding: 5rem 2rem;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') center/cover no-repeat;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero button {
      padding: 0.8rem 2rem;
      font-size: 1rem;
      background-color: #d07f6e;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
    .section {
      padding: 3rem 2rem;
      text-align: center;
    }
    .section h3 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #ffb7a3;
    }
    .product {
      background-color: #2d2d2d;
      padding: 2rem;
      margin-top: 2rem;
      border-radius: 10px;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }
    .product button {
      margin-top: 1rem;
      padding: 0.6rem 1.5rem;
      background-color: #e89c93;
      border: none;
      border-radius: 5px;
      color: white;
      cursor: pointer;
    }
    footer {
      background-color: #3e2c29;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      color: #f8e1dc;
    }
  </style>
</head>
<body>

  <header>
    <h1>Home Bakery</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Menu</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Home Bakery</h2>
    <button>ORDER NOW</button>
  </section>

  <section class="section">
    <h3>OUR Specials</h3>
    <p>Discover our delightful range of fresh bakery items made with love and passion.</p>
  </section>

  <section class="section">
    <h3>Featured Product</h3>
    <div class="product">
      <h4>Chocolate Fudge Cake</h4>
      <p>Rich, moist, and full of flavor – our best-selling cake!</p>
      <button>Order Now</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Home Bakery. All rights reserved.</p>
  </footer>

</body>
</html>
