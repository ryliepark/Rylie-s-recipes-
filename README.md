# Rylie-s-recipes-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Recipes</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #fafafa;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #fff;
      box-shadow: 0 1px 5px rgba(0, 0, 0, 0.05);
      padding: 40px 20px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 1px;
    }

    nav {
      display: flex;
      justify-content: center;
      background: #ffffff;
      border-top: 1px solid #eee;
      border-bottom: 1px solid #eee;
      margin-top: 20px;
    }

    nav a {
      text-decoration: none;
      color: #555;
      padding: 15px 20px;
      font-weight: bold;
      transition: color 0.2s ease;
    }

    nav a:hover {
      color: #000;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .recipe {
      background: #fff;
      padding: 20px;
      margin-bottom: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.03);
    }

    .recipe h2 {
      margin-top: 0;
    }

    .category {
      font-size: 0.9rem;
      color: #999;
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Recipe Collection</h1>
    <p>Simple. Delicious. You.</p>
  </header>

  <nav>
    <a href="#sweet">Sweet</a>
    <a href="#savory">Savory</a>
    <a href="#experimental">Experimental</a>
  </nav>

  <div class="container">
    <section id="sweet">
      <div class="recipe">
        <div class="category">Sweet</div>
        <h2>Vanilla Cardamom Cloud Cookies</h2>
        <p>Light, chewy, with a whisper of spice. Perfect with tea or midnight thoughts.</p>
      </div>
    </section>

    <section id="savory">
      <div class="recipe">
        <div class="category">Savory</div>
        <h2>Roasted Fennel & Olive Flatbread</h2>
        <p>Earthy, salty, and deeply aromatic — a rustic twist on pizza night.</p>
      </div>
    </section>

    <section id="experimental">
      <div class="recipe">
        <div class="category">Experimental</div>
        <h2>Cryo-Crusted Cactus Pear Churro Bites</h2>
        <p>Sweet, smoky, and totally out-of-this-world. A crunchy chilled shell gives way to a warm mole pudding core. Unforgettable.</p>
      </div>
    </section>
  </div>

  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>
</body>
</html>