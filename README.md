# Protofoilio
only for graphic designers 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Alok's Design Portfolio</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #fff;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 24px;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #0077cc;
      font-weight: bold;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    h2 {
      margin-top: 40px;
      font-size: 28px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .card {
      background: #fff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }
    .card img {
      width: 100%;
      border-radius: 8px;
    }
    .card h3 {
      margin: 10px 0 5px;
    }
    .card p {
      font-size: 14px;
      color: #555;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      background: #fff;
      margin-top: 40px;
    }
    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav a {
        margin-left: 0;
        margin-right: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🎨 Alok's Portfolio</h1>
    <nav>
      <a href="#uiux">UI/UX</a>
      <a href="#gameui">Game UI</a>
    </nav>
  </header>

  <div class="container">
    <section id="about">
      <h2>👋 Welcome</h2>
      <p>I’m Alok, a coder, web/app/game developer with a passion for design. Here you’ll find my UI/UX and Game UI projects.</p>
    </section>

    <section id="uiux">
      <h2>💡 UI/UX Projects</h2>
      <div class="grid">
        <div class="card">
          <img src="bank-app.jpg" alt="Banking App UI">
          <h3>Mobile Banking App</h3>
          <p>Modern UI for financial operations: transfers, cards, dark mode.</p>
        </div>
        <div class="card">
          <img src="saas-dashboard.jpg" alt="SaaS Dashboard">
          <h3>SaaS Dashboard</h3>
          <p>Clean layout for managing analytics and KPIs with charts.</p>
        </div>
      </div>
    </section>

    <section id="gameui">
      <h2>🎮 Game UI Projects</h2>
      <div class="grid">
        <div class="card">
          <img src="hud-ui.jpg" alt="Game HUD">
          <h3>Fantasy Game HUD</h3>
          <p>Includes HP, XP, Mana bars for immersive game experience.</p>
        </div>
        <div class="card">
          <img src="inventory-ui.jpg" alt="Inventory System">
          <h3>Inventory System</h3>
          <p>Grid-style drag and drop inventory for survival game UI.</p>
        </div>
      </div>
    </section>
  </div>

  <footer>
    © 2025 Alok Baranwal | Built with HTML & CSS
  </footer>

</body>
</html>
