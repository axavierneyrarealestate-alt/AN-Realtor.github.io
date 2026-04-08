<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AN Realtor | Axavier Neyra</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #000;
    }

    header {
      background-color: #000;
      color: #d4af37;
      padding: 15px;
      text-align: center;
    }

    header img {
      height: 70px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #111;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') no-repeat center/cover;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
    }

    .hero h1 {
      font-size: 3em;
      background: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 10px;
    }

    section {
      padding: 50px;
      max-width: 1100px;
      margin: auto;
    }

    h2 {
      color: #d4af37;
    }

    .services div {
      margin-bottom: 30px;
      padding: 20px;
      border-left: 4px solid #d4af37;
      background: #f9f9f9;
    }

    .listings {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      border: 1px solid #ddd;
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
    }

    .instagram {
      text-align: center;
      margin-top: 20px;
    }

    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <img src="logo.png" alt="AN Realtor Logo">
  <p>Axavier Neyra</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#listings">Listings</a>
  <a href="#location">Location</a>
</nav>

<div class="hero">
  <h1>Luxury Real Estate in El Paso</h1>
</div>

<section id="services" class="services">
  <h2>Services</h2>

  <div>
    <h3>Helping Buyers</h3>
    <p>I guide buyers through every step of the home buying process, making it smooth and stress-free. From property search to closing, I ensure you understand every detail and secure the best deal possible.</p>
  </div>

  <div>
    <h3>Helping Sellers</h3>
    <p>I help sellers maximize value through detailed CMAs, targeted advertising, professional marketing, and strong promotional strategies including signage and exposure to the right buyers.</p>
  </div>

  <div>
    <h3>Helping Investors</h3>
    <p>I provide a full-service investment experience. With a team including a lender and accountant, we ensure your investments are aligned properly and built to achieve your financial goals.</p>
  </div>
</section>

<section id="listings">
  <h2>Featured Listings</h2>
  <div class="listings">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994" alt="House">
      <div class="card-content">
        <h3>Property Address</h3>
        <p>Status: For Sale</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1572120360610-d971b9d7767c" alt="House">
      <div class="card-content">
        <h3>Property Address</h3>
        <p>Status: Sold</p>
      </div>
    </div>

  </div>
</section>

<section id="location">
  <h2>Office Location</h2>
  <iframe src="https://www.google.com/maps?q=El+Paso&output=embed"></iframe>
</section>

<section class="instagram">
  <h2>Follow Me</h2>
  <a href="https://www.instagram.com/p/DWSung3Dt6T/?hl=en" target="_blank">View on Instagram</a>
</section>

<footer>
  <p>&copy; 2026 AN Realtor | Axavier Neyra</p>
</footer>

</body>
</html>

