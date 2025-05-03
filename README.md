<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alicia's Handmade Treasures</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #fff3cd, #ffe0e9);
      color: #333;
    }
    header {
      background-color: #ff6f91;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 2em;
    }
    section {
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #ff6f91;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .card {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 20px;
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .order-form {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-top: 40px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #ff6f91;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  Alicia's Handmade Treasures
</header>

<section>
  <h2>Featured Creations</h2>
  <div class="grid">
    <div class="card">
      <img src="images/candles.jpg" alt="Scented Candles">
      <h3>Scented Candles</h3>
      <p>Hand-poured, soul-soothing candles in a variety of scents to elevate any room.</p>
      <a href="#order">Order Now</a>
    </div>
    <div class="card">
      <img src="images/inspiration-board.jpg" alt="Inspirational Boards">
      <h3>Inspirational Boards</h3>
      <p>Faith-based visual boards with affirmations and artwork to spark daily motivation.</p>
      <a href="#order">Order Now</a>
    </div>
    <div class="card">
      <img src="images/jewelry.jpg" alt="Handmade Jewelry">
      <h3>Handmade Jewelry</h3>
      <p>Stylish memory wire bracelets, beaded earrings, and statement pieces that shine.</p>
      <a href="#order">Order Now</a>
    </div>
    <div class="card">
      <img src="images/keychains.jpg" alt="Custom Keychains">
      <h3>Custom Keychains</h3>
      <p>Unique resin and charm keychains perfect for gifts or a pop of personality.</p>
      <a href="#order">Order Now</a>
    </div>
    <div class="card">
      <img src="images/docks.jpg" alt="Charging Docks">
      <h3>Charging Docks</h3>
      <p>Decorative yet functional phone docks made with love and vibrant design.</p>
      <a href="#order">Order Now</a>
    </div>
    <div class="card">
      <img src="images/baskets.jpg" alt="All-Occasion Baskets">
      <h3>All-Occasion Baskets</h3>
      <p>Perfectly curated gift baskets for birthdays, holidays, and healing moments.</p>
      <a href="#order">Order Now</a>
    </div>
    <div class="card">
      <img src="images/wig-tutorials.jpg" alt="Wig Tutorials">
      <h3>Wig Tutorials</h3>
      <p>Step-by-step styling tutorials for flawless wig transformations, beginner-friendly.</p>
      <a href="#order">Order Now</a>
    </div>
  </div>
</section>

<section id="order" class="order-form">
  <h2>Place Your Order</h2>
  <form action="mailto:aliciasandiferart@gmail.com" method="POST" enctype="text/plain">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="product">Which item would you like to order?</label><br>
    <select id="product" name="product">
      <option value="candles">Scented Candles</option>
      <option value="jewelry">Handmade Jewelry</option>
      <option value="keychains">Custom Keychains</option>
      <option value="baskets">All-Occasion Baskets</option>
      <option value="inspirational">Inspirational Boards</option>
      <option value="docks">Charging Docks</option>
      <option value="wig">Wig Tutorials</option>
    </select><br><br>

    <label for="message">Message or Special Requests:</label><br>
    <textarea id="message" name="message" rows="4" cols="40"></textarea><br><br>

    <input type="submit" value="Send Order Request">
  </form>
</section>

<footer>
  Created with love by Alicia Gates-Sandifer | Contact: aliciasandiferart@gmail.com
</footer>

</body>
</html>
