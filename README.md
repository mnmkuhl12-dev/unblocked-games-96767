<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Unblocked Games G+</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #0f0f0f, #1a1a2e);
      color: #f1f1f1;
      text-align: center;
    }
    header {
      background: #111;
      padding: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.8);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 {
      margin: 0;
      font-size: 2.8rem;
      color: #00ffcc;
      text-shadow: 0 0 10px #00ffcc;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #00ffcc;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ff0099;
    }
    .container {
      padding: 30px 10px;
    }
    .container h2 {
      font-size: 2rem;
      color: #ff0099;
      margin-bottom: 20px;
      text-shadow: 0 0 8px #ff0099;
    }
    .game-card {
      display: inline-block;
      background: #1c1c1c;
      margin: 15px;
      padding: 15px;
      border-radius: 12px;
      width: 320px;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
      transition: transform 0.2s, box-shadow 0.2s;
      vertical-align: top;
    }
    .game-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px rgba(0,255,204,0.6);
    }
    .game-card h3 {
      margin-top: 10px;
      font-size: 1.3rem;
      color: #00ffcc;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 8px;
      background: #000;
    }
    button {
      margin-top: 8px;
      padding: 8px 12px;
      background: #00ffcc;
      color: #000;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.2s;
    }
    button:hover {
      background: #ff0099;
      color: #fff;
    }
    .fullscreen-modal {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: #000;
      z-index: 9999;
    }
    .fullscreen-modal iframe {
      width: 100%;
      height: 100%;
      border: none;
      border-radius: 0;
    }
    .close-btn {
      position: absolute;
      top: 10px;
      right: 20px;
      background: red;
      color: #fff;
      border: none;
      font-size: 18px;
      padding: 8px 12px;
      cursor: pointer;
      border-radius: 6px;
      z-index: 10000;
    }
  </style>
</head>
<body>
  <header>
    <h1>🎮 Unblocked Games G+</h1>
    <nav>
      <a href="#arcade">Arcade</a>
      <a href="#action">Action</a>
      <a href="#racing">Racing</a>
      <a href="#3d">3D</a>
    </nav>
  </header>

  <!-- Arcade Games -->
  <div class="container" id="arcade">
    <h2>🕹 Arcade Games</h2>
    <div class="game-card">
      <iframe src="https://funhtml5games.com?embed=snake"></iframe>
      <h3>Snake</h3>
      <button onclick="openFullscreen('https://funhtml5games.com?embed=snake')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://funhtml5games.com?embed=flappy"></iframe>
      <h3>Flappy Bird</h3>
      <button onclick="openFullscreen('https://funhtml5games.com?embed=flappy')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://scratch.mit.edu/projects/658355498/embed"></iframe>
      <h3>Geometry Dash Wave</h3>
      <button onclick="openFullscreen('https://scratch.mit.edu/projects/658355498/embed')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://amongusplay.online/"></iframe>
      <h3>Among Us</h3>
      <button onclick="openFullscreen('https://amongusplay.online/')">Fullscreen</button>
    </div>
  </div>

  <!-- Action Games -->
  <div class="container" id="action">
    <h2>🔫 Action / Shooter</h2>
    <div class="game-card">
      <iframe src="https://shellshock.io/"></iframe>
      <h3>Shellshock.io</h3>
      <button onclick="openFullscreen('https://shellshock.io/')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://1v1.lol/"></iframe>
      <h3>1v1.LOL</h3>
      <button onclick="openFullscreen('https://1v1.lol/')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://krunker.io/"></iframe>
      <h3>Krunker.io</h3>
      <button onclick="openFullscreen('https://krunker.io/')">Fullscreen</button>
    </div>
  </div>

  <!-- Racing Games -->
  <div class="container" id="racing">
    <h2>🏎 Racing Games</h2>
    <div class="game-card">
      <iframe src="https://moto3m.com/embed/moto-x3m-3"></iframe>
      <h3>Moto X3M</h3>
      <button onclick="openFullscreen('https://moto3m.com/embed/moto-x3m-3')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://y8.com/embed/slope"></iframe>
      <h3>Slope</h3>
      <button onclick="openFullscreen('https://y8.com/embed/slope')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://smashkarts.io/"></iframe>
      <h3>Smash Karts</h3>
      <button onclick="openFullscreen('https://smashkarts.io/')">Fullscreen</button>
    </div>
  </div>

  <!-- 3D Games -->
  <div class="container" id="3d">
    <h2>🌐 3D Games</h2>
    <div class="game-card">
      <iframe src="https://classic.minecraft.net/"></iframe>
      <h3>Minecraft Classic</h3>
      <button onclick="openFullscreen('https://classic.minecraft.net/')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://run3.io/"></iframe>
      <h3>Run 3</h3>
      <button onclick="openFullscreen('https://run3.io/')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://ev.io/"></iframe>
      <h3>Ev.io</h3>
      <button onclick="openFullscreen('https://ev.io/')">Fullscreen</button>
    </div>
    <div class="game-card">
      <iframe src="https://venge.io/"></iframe>
      <h3>Venge.io</h3>
      <button onclick="openFullscreen('https://venge.io/')">Fullscreen</button>
    </div>
  </div>

  <!-- Fullscreen Modal -->
  <div class="fullscreen-modal" id="fullscreenModal">
    <button class="close-btn" onclick="closeFullscreen()">✖ Close</button>
    <iframe id="fullscreenFrame"></iframe>
  </div>

  <script>
    function openFullscreen(url) {
      const modal = document.getElementById("fullscreenModal");
      const frame = document.getElementById("fullscreenFrame");
      frame.src = url;
      modal.style.display = "block";
    }
    function closeFullscreen() {
      const modal = document.getElementById("fullscreenModal");
      const frame = document.getElementById("fullscreenFrame");
      frame.src = "";
      modal.style.display = "none";
    }
    document.addEventListener("keydown", e => {
      if (e.key === "Escape") closeFullscreen();
    });
  </script>
</body>
</html>
