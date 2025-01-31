<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luxury Travel Agency</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">VIP Luxury Travels</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#destinations">Destinations</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Experience Unmatched Luxury</h1>
      <p>Your journey to the world's most exquisite destinations begins here.</p>
      <button class="btn-primary">Book Your VIP Experience</button>
    </div>
  </section>

  <!-- Destinations Section -->
  <section id="destinations" class="destinations">
    <h2>Exclusive Destinations</h2>
    <div class="destination-cards">
      <div class="destination-card">
        <img src="dubai.jpg" alt="Dubai">
        <h3>Dubai</h3>
        <p>Indulge in the opulence and grandeur of Dubai’s luxurious resorts, fine dining, and iconic landmarks.</p>
        <button class="btn-secondary">Discover Dubai</button>
      </div>
      <div class="destination-card">
        <img src="thailand.jpg" alt="Thailand">
        <h3>Thailand</h3>
        <p>Relax in the tranquility of private beach resorts, explore exotic islands, and enjoy world-class luxury.</p>
        <button class="btn-secondary">Explore Thailand</button>
      </div>
      <div class="destination-card">
        <img src="istanbul.jpg" alt="Istanbul">
        <h3>Istanbul</h3>
        <p>Experience the perfect blend of culture, history, and elegance in Istanbul’s most luxurious accommodations.</p>
        <button class="btn-secondary">Visit Istanbul</button>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="about-us">
    <h2>About Us</h2>
    <p>At VIP Luxury Travels, we specialize in providing exclusive travel experiences for our elite clientele. Every detail is meticulously crafted to ensure a seamless journey. From private jets to bespoke experiences, we offer unparalleled service for those who demand the best.</p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact-us">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <input type="text" id="name" placeholder="Your Name" required>
      <input type="email" id="email" placeholder="Your Email" required>
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn-primary">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 VIP Luxury Travels. All Rights Reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
/* General Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  color: #333;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

/* Header */
header {
  background-color: #333;
  color: white;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header .logo {
  font-size: 24px;
  font-weight: 700;
}

header nav ul {
  display: flex;
  list-style: none;
}

header nav ul li {
  margin-left: 30px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.3s ease;
}

header nav ul li a:hover {
  color: #ff7f50;
}

/* Hero Section */
.hero {
  background: url('luxury-travel.jpg') no-repeat center center/cover;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

.hero-content h1 {
  font-size: 4rem;
  font-weight: 700;
}

.hero-content p {
  font-size: 1.5rem;
  margin: 20px 0;
}

.hero .btn-primary {
  background-color: #ff7f50;
  color: white;
  padding: 15px 30px;
  font-size: 18px;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.hero .btn-primary:hover {
  background-color: #ff6347;
}

/* Destinations Section */
.destinations {
  padding: 60px 20px;
  text-align: center;
  background-color: #f9f9f9;
}

.destinations h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 40px;
}

.destination-cards {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.destination-card {
  width: 30%;
  margin: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.destination-card:hover {
  transform: translateY(-10px);
}

.destination-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.destination-card h3 {
  font-size: 1.8rem;
  font-weight: 600;
  margin: 20px 0;
}

.destination-card p {
  font-size: 1rem;
  color: #555;
}

.destination-card .btn-secondary {
  background-color: #333;
  color: white;
  padding: 12px 25px;
  border: none;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.destination-card .btn-secondary:hover {
  background-color: #ff7f50;
}

/* About Us Section */
.about-us {
  padding: 60px 20px;
  text-align: center;
  background-color: #fff;
}

.about-us h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 20px;
}

.about-us p {
  font-size: 1.2rem;
  line-height: 1.8;
  color: #555;
  max-width: 800px;
  margin: 0 auto;
}

/* Contact Section */
.contact-us {
  padding: 60px 20px;
  background-color: #f9f9f9;
  text-align: center;
}

.contact-us h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 40px;
}

.contact-us form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.contact-us input, .contact-us textarea {
  width: 100%;
  max-width: 600px;
  padding: 15px;
  margin: 10px 0;
  font-size: 1rem;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.contact-us button {
  background-color: #ff7f50;
  color: white;
  padding: 15px 30px;
  font-size: 18px;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact-us button:hover {
  background-color: #ff6347;
}

/* Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}
