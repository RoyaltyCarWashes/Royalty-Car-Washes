# Royalty-Car-Washes
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Royalty Car Washes</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
    }
    header {
      background: linear-gradient(to right, #1c1c1c, #444);
      color: gold;
      padding: 30px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
    }
    nav {
      background: #222;
      color: white;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      color: gold;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1570129477492-45c003edd2be') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px #000;
      font-size: 2.5em;
      font-weight: bold;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .service {
      background: white;
      padding: 20px;
      margin: 15px;
      border-radius: 10px;
      width: 280px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .service h3 {
      color: #333;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: 20px auto;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background-color: #222;
      color: gold;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #333;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Royalty Car Washes</h1>
  <p>Your car deserves the royal treatment</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#about">About Us</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  Drive Clean, Ride Royal
</div>

<section id="services">
  <h2 style="text-align:center;">Our Services</h2>
  <div class="services">
    <div class="service">
      <h3>Basic Wash</h3>
      <p>Exterior wash and rinse. Quick and clean.</p>
      <p><strong>$10</strong></p>
    </div>
    <div class="service">
      <h3>Deluxe Wash</h3>
      <p>Exterior and interior cleaning, vacuum included.</p>
      <p><strong>$25</strong></p>
    </div>
    <div class="service">
      <h3>Royal Treatment</h3>
      <p>Full detail, wax, tire shine, and more.</p>
      <p><strong>$50</strong></p>
    </div>
  </div>
</section>

<section id="about">
  <h2 style="text-align:center;">About Us</h2>
  <p style="text-align:center; max-width: 700px; margin: auto;">
    At Royalty Car Washes, we believe every car should shine like royalty. With premium products, top-tier customer service, and detail-oriented staff, we’ve been serving our community with pride and sparkle since 2020.
  </p>
</section>

<section id="contact">
  <h2 style="text-align:center;">Contact or Book a Wash</h2>
  <form action="https://formsubmit.co/Royalty.Car.Washes@gmail.com" method="POST">
    <!-- Replace your-email@example.com with your real email address -->
    <input type="hidden" name="_captcha" value="false">
    <label for="name">Name:</label>
    <input type="text" name="name" required>

    <label for="email">Email:</label>
    <input type="email" name="email" required>

    <label for="phone">Phone Number:</label>
    <input type="text" name="phone" required>

    <label for="service">Service Requested:</label>
    <input type="text" name="service" placeholder="e.g., Deluxe Wash" required>

    <label for="message">Additional Info / Preferred Date:</label>
    <textarea name="message" rows="5" required></textarea>

    <button type="submit">Send Booking Request</button>
  </form>
  <p style="text-align:center;">Or call us: (123) 456-7890</p>
</section>

<footer>
  &copy; 2025 Royalty Car Washes. All rights reserved.
</footer>

</body>
</html>
