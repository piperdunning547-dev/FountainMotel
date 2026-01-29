<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sunrise Boutique Hotel</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header class="header">
    <h1>Sunrise Boutique Hotel</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#rooms">Rooms</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-text">
      <h2>Your Comfort, Our Priority</h2>
      <p>Relax. Unwind. Enjoy your stay.</p>
      <a href="#contact" class="btn">Book Now</a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="section">
    <h2>About Us</h2>
    <p>
      Sunrise Boutique Hotel is a cozy and elegant hotel offering comfort,
      quality service, and a warm atmosphere for travelers and families.
    </p>
  </section>

  <!-- Rooms -->
  <section id="rooms" class="section gray">
    <h2>Our Rooms</h2>
    <div class="cards">
      <div class="card">
        <h3>Standard Room</h3>
        <p>Comfortable room with free Wi-Fi and breakfast.</p>
      </div>
      <div class="card">
        <h3>Deluxe Room</h3>
        <p>Spacious room with city view and king-size bed.</p>
      </div>
      <div class="card">
        <h3>Suite</h3>
        <p>Luxury suite with living area and premium services.</p>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="section">
    <h2>Services</h2>
    <ul class="services">
      <li>24/7 Reception</li>
      <li>Free Wi-Fi</li>
      <li>Room Service</li>
      <li>Airport Pickup</li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact" class="section gray">
    <h2>Contact Us</h2>
    <p>Email: info@sunrisehotel.com</p>
    <p>Phone: +1 234 567 890</p>
    <p>Address: 123 Beach Road, City</p>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>© 2026 Sunrise Boutique Hotel. All rights reserved.</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  line-height: 1.6;
  color: #333;
}

.header {
  background: #2c3e50;
  color: white;
  padding: 15px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
}

.hero {
  background: url("images/hero.jpg") center/cover no-repeat;
  height: 70vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-text {
  background: rgba(0, 0, 0, 0.6);
  color: white;
  padding: 30px;
  text-align: center;
}

.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 10px 20px;
  background: #e67e22;
  color: white;
  text-decoration: none;
  border-radius: 4px;
}

.section {
  padding: 50px 20px;
  text-align: center;
}

.gray {
  background: #f4f4f4;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  background: white;
  padding: 20px;
  width: 250px;
  border-radius: 5px;
}

.services {
  list-style: none;
}

.services li {
  margin: 10px 0;
}

.footer {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 15px;
}
