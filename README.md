# LiveLab 4: Responsive Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nomadiq Travel Destinations</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Lora:wght@500&family=Open+Sans:wght@400;600&display=swap');

    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #f9fdf9;
      color: #2f3e46;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      padding: 15px 20px;
      background: linear-gradient(90deg, #74c69d, #52b788, #40916c);
      color: white;
      transition: background 0.4s ease;
    }

    header:hover {
      background: linear-gradient(90deg, #52b788, #40916c, #2d6a4f);
    }

    .logo {
      font-size: 1.6rem;
      font-family: 'Lora', serif;
      font-weight: 500;
      margin-bottom: 10px;
      transition: transform 0.3s ease;
    }

    .logo:hover {
      transform: scale(1.05);
    }

    .logo span {
      margin-right: 8px;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    nav a {
      margin: 5px 12px;
      text-decoration: none;
      color: white;
      font-weight: 600;
      transition: color 0.3s, transform 0.3s;
      font-family: 'Open Sans', sans-serif;
    }

    nav a:hover {
      color: #d8f3dc;
      transform: translateY(-2px);
    }

    .hero {
      text-align: center;
      padding: 80px 20px;
      background-color: #e6f2ef;
      transition: background-color 0.4s ease;
    }

    .hero:hover {
      background-color: #dff7f0;
    }

    .hero h1 {
      font-family: 'Lora', serif;
      font-size: 2.2rem;
      margin-bottom: 20px;
      color: #1b4332;
      letter-spacing: 1px;
    }

    .hero p {
      font-size: 1.1rem;
      max-width: 85%;
      margin: 0 auto 30px;
      line-height: 1.8;
      color: #2f3e46;
    }

    .hero button {
      background-color: #40916c;
      color: white;
      border: none;
      padding: 14px 28px;
      font-size: 1.1rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s, transform 0.3s;
    }

    .hero button:hover {
      background-color: #2d6a4f;
      transform: scale(1.05);
    }

    .about {
      padding: 50px 20px;
      text-align: center;
      background-color: #f0fdf4;
    }

    .about h2 {
      font-family: 'Lora', serif;
      font-size: 1.8rem;
      margin-bottom: 20px;
      color: #1b4332;
    }

    .about p {
      font-size: 1.05rem;
      max-width: 90%;
      margin: 0 auto 30px;
      line-height: 1.7;
      color: #2f3e46;
    }

    .about button {
      background-color: #52b788;
      color: white;
      border: none;
      padding: 14px 28px;
      font-size: 1.1rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s, transform 0.3s;
    }

    .about button:hover {
      background-color: #40916c;
      transform: scale(1.05);
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 0 auto;
    }

    /* Responsive layout for screens 600px and wider */
    @media (min-width: 600px) {
      .hero {
        padding: 120px 40px;
      }

      .hero h1 {
        font-size: 2.8rem;
      }

      .hero p {
        font-size: 1.2rem;
        max-width: 700px;
      }

      .about {
        padding: 70px 40px;
      }

      .about h2 {
        font-size: 2.2rem;
      }

      .about p {
        font-size: 1.15rem;
        max-width: 700px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <span>🌍</span> Nomadiq Travel Destinations
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#destinations">Destinations</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Explore Sustainable Travel</h1>
    <p>Discover how mindful journeys can connect you with the world while preserving it for future generations. At Nomadiq Travel Destinations, we believe in eco-friendly adventures that celebrate nature, support local communities, and inspire responsible exploration.</p>
    <button onclick="alert('Start planning your trip with Nomadiq!')">Plan Your Trip</button>
  </section>

  <section class="about" id="about">
    <h2>About Nomadiq Travel Destinations</h2>
    <p>Nomadiq Travel Destinations is dedicated to creating eco-friendly travel experiences that honor the planet. We focus on sustainable tourism practices, from supporting local cultures to minimizing environmental impact, so every journey makes a positive difference.</p>
    <button onclick="alert('Learn more about Nomadiq Travel Destinations!')">Learn More</button>
  </section>
</body>
</html>
