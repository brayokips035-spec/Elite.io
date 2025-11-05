<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>LivingWord Bible</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }
    header {
      background: rgba(0, 0, 0, 0.6);
      padding: 1em 2em;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: #fff;
      margin: 0 1em;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      padding: 6em 2em;
      text-align: center;
      background: rgba(0, 0, 0, 0.5);
    }
    .hero h1 {
      font-size: 3em;
      margin-bottom: 0.5em;
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 1em;
    }
    .hero button {
      padding: 0.8em 1.5em;
      margin: 0.5em;
      background: #FFD700;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }
    section {
      padding: 2em;
      max-width: 1000px;
      margin: auto;
      background: rgba(0, 0, 0, 0.6);
      margin-top: 2em;
      border-radius: 10px;
    }
    .verse {
      font-style: italic;
      font-size: 1.5em;
      text-align: center;
      margin: 2em 0;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2em;
    }
    footer {
      background: rgba(0, 0, 0, 0.6);
      text-align: center;
      padding: 2em;
      margin-top: 2em;
    }
    input[type="email"] {
      padding: 0.5em;
      width: 250px;
    }
    .newsletter button {
      padding: 0.5em 1em;
      background: #FFD700;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h2>LivingWord</h2>
    <nav>
      <a href="#">Home</a>
      <a href="#">Read the Bible</a>
      <a href="#">Devotionals</a>
      <a href="#">Sermons</a>
      <a href="#">Prayer</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Discover the Living Word of God</h1>
    <p>Explore scripture, grow in faith, and connect with believers worldwide.</p>
    <button>Start Reading</button>
    <button>Join Devotionals</button>
  </div>

  <section>
    <div class="verse">“Your word is a lamp to my feet and a light to my path.” — Psalm 119:105</div>
  </section>

  <!-- Additional sections go here -->

  <footer>
    <p>&copy; 2025 LivingWord Bible. All rights reserved.</p>
    <p>Follow us: Facebook | Instagram | YouTube</p>
  </footer>

</body>
</html>
