# pessicon
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PESCCICON - Christ College of Engineering</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      margin: 0;
      background: #f5f5f5; /* Smokey light grey */
      color: #333;
    }

    header {
      background: white;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ccc;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #e6541b;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #444;
      font-weight: 500;
    }

    .hero {
      background: linear-gradient(to right, #f26b1d, #f58c2f);
      color: white;
      padding: 80px 20px 40px;
      text-align: center;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      max-width: 800px;
      margin: 0 auto 30px;
    }

    .filters {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }

    .filters select, .filters button {
      padding: 10px;
      border-radius: 5px;
      border: none;
      min-width: 200px;
    }

    .filters button {
      background: #e6541b;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }

    .features, .topics {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 40px 20px;
      gap: 20px;
    }

    .feature-box, .topic-box {
      background: white;
      padding: 15px 20px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      text-align: center;
      min-width: 180px;
      transition: transform 0.3s ease;
    }

    .feature-box:hover, .topic-box:hover {
      transform: translateY(-5px);
    }

    .topic-box {
      background: linear-gradient(to right, #e6541b, #f58c2f);
      color: white;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 16px;
      font-weight: 500;
      background: white;
      color: #555;
      border-top: 1px solid #ddd;
    }

    footer span {
      color: #e6541b;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">PESCCICON</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Add Event</a>
      <a href="#">Subscribe</a>
      <a href="#">Contact</a>
      <a href="#">Blog</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to PESCCICON 2025</h1>
    <p>
      Organized by the <strong>Electrical Department</strong> of <strong>Christ College of Engineering, Irinjalakuda, Thrissur</strong>.<br />
      Proudly hosting delegates from prestigious institutions like <strong>IITs, NITs</strong>, and leading research centers across India.
    </p>
    <div class="filters">
      <select>
        <option>Choose a Country</option>
        <option>India</option>
        <option>USA</option>
        <option>UK</option>
      </select>
      <select>
        <option>Choose a Category</option>
        <option>Medical</option>
        <option>Technology</option>
        <option>Electrical</option>
      </select>
      <select>
        <option>Choose a Topic</option>
        <option>Power Systems</option>
        <option>IoT in Energy</option>
        <option>AI in Electrical</option>
      </select>
      <button>Search</button>
    </div>
  </section>

  <section class="features">
    <div class="feature-box">Conference in India</div>
    <div class="feature-box">Scopus Indexed Journal</div>
    <div class="feature-box">Scopus Conferences</div>
    <div class="feature-box">Online Conferences</div>
    <div class="feature-box">Upcoming Events</div>
    <div class="feature-box">UGC Care Journals</div>
  </section>

  <section class="topics">
    <div class="topic-box">Power Electronics</div>
    <div class="topic-box">Smart Grid</div>
    <div class="topic-box">Electric Vehicles</div>
    <div class="topic-box">AI & IoT</div>
    <div class="topic-box">Renewable Energy</div>
  </section>

  <footer>
    &copy; 2025 <span>PESCCICON</span> | Christ College of Engineering, Thrissur
  </footer>

</body>
</html>
