# Index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Fun Website</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: #fff;
    }
    header {
      background: rgba(0,0,0,0.4);
      padding: 40px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      background: rgba(0,0,0,0.7);
      padding: 15px;
      text-align: center;
      position: sticky;
      top: 0;
    }
    nav a {
      color: #ffd166;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #06d6a0;
    }
    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
      background: rgba(255,255,255,0.1);
      border-radius: 12px;
      margin-bottom: 40px;
    }
    h2 {
      border-bottom: 2px solid #ffd166;
      padding-bottom: 10px;
    }
    footer {
      background: rgba(0,0,0,0.7);
      text-align: center;
      padding: 15px;
    }
    iframe {
      width: 100%;
      height: 500px;
      border: none;
      border-radius: 12px;
      margin-top: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>🎮 My Fun Website 🎮</h1>
    <p>Play games & explore my projects 🚀</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#games">Games</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm learning how to make websites and games. This website is my playground where I test cool projects and fun games.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li>🔫 Mini Shooting Game</li>
      <li>🌐 Personal Website</li>
      <li>📱 More games coming soon...</li>
    </ul>
  </section>

  <section id="games">
    <h2>Play Games</h2>
    <p>Enjoy some classic games right here 👇</p>

    <h3>♟️ Chess</h3>
    <iframe src="https://playpager.com/embed/chess/index.html"></iframe>

    <h3>🎲 Ludo</h3>
    <iframe src="https://playpager.com/embed/ludo/index.html"></iframe>

    <h3>🐍 Snakes & Ladders</h3>
    <iframe src="https://playpager.com/embed/snakes-and-ladders/index.html"></iframe>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>You can reach me at: <strong>myemail@example.com</strong></p>
  </section>

  <footer>
    <p>&copy; 2025 My Fun Website | Made with ❤️ in HTML & CSS</p>
  </footer>

</body>
</html>