<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name – Car Salesman</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #34495e;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
    }
    .inventory img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    form input, form textarea {
      display: block;
      width: 100%;
      margin: 10px 0;
      padding: 10px;
    }
    form button {
      padding: 10px 20px;
      background: #2980b9;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>Professional Car Salesman – Helping You Find the Right Ride</p>
  </header>

  <nav>
    <a href="#about">About Me</a>
    <a href="#inventory">Inventory</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Your Name, a passionate and experienced car salesman dedicated to making your car buying experience smooth, honest, and pressure-free. With X years in the auto industry, I take pride in helping each customer find the perfect vehicle.</p>
  </section>

  <section id="inventory" class="inventory">
    <h2>Featured Vehicles</h2>
    <img src="https://via.placeholder.com/800x400" alt="Car example"/>
    <p>2022 Toyota Camry – $24,995 – Excellent condition, low miles</p>
    <img src="https://via.placeholder.com/800x400" alt="Car example"/>
    <p>2021 Honda Accord – $22,995 – Certified Pre-Owned</p>
    <!-- Add more cars as needed -->
  </section>

  <section id="testimonials">
    <h2>What Clients Say</h2>
    <blockquote>“Your Name was amazing! He helped me get a great deal and made the whole process simple.” – Happy Customer</blockquote>
    <blockquote>“Honest, knowledgeable, and super helpful. Highly recommend!” – Satisfied Buyer</blockquote>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Your Name – Car Salesman</p>
  </footer>
</body>
</html>