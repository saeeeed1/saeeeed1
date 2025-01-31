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
