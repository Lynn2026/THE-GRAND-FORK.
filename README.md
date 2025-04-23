# THE-GRAND-FORK.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Grand Fork</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>The Grand Fork</h1>
    <p>Luxury Boutique Cultural Dining Experience</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#events">Events</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>The Grand Fork blends fine dining, cultural elegance, and live music under a black and gold royal theme.</p>
  </section>

  <section id="menu">
    <h2>Menu Preview</h2>
    <p>Seared Scallops | Truffle Risotto | Royal Lamb Chops | Vegan Mediterranean Platter</p>
  </section>

  <section id="events">
    <h2>Private Events</h2>
    <p>Host your exclusive event with luxury service and curated menus.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@thegrandfork.com</p>
    <p>Instagram: @TheGrandFork</p>
  </section>

  <footer>
    <p>&copy; 2026 The Grand Fork. All rights reserved.</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: 'Garamond', serif;
  background-color: #000;
  color: #fff;
  scroll-behavior: smooth;
}
header {
  background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
  height: 100vh;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: gold;
}
nav {
  background-color: #000;
  padding: 10px 0;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 1000;
}
nav a {
  color: gold;
  margin: 0 15px;
  text-decoration: none;
  font-size: 18px;
}
section {
  padding: 60px 20px;
  text-align: center;
}
section h2 {
  color: gold;
  font-size: 36px;
  margin-bottom: 20px;
}
footer {
  text-align: center;
  padding: 20px;
  font-size: 14px;
  background-color: #111;
  color: gold;
}
