<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  header {
      background-color: #1e1e2f;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
    }

    nav a {
      color: #fff;
      margin-left: 1rem;
      text-decoration: none;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1606813904235-870c12e6dacc') no-repeat center center/cover;
      height: 300px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      font-size: 2rem;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }

    .container {
      padding: 2rem;
    }

    .game-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
    }

    .game-card {
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }

    .game-card:hover {
      transform: scale(1.05);
    }

    .game-card img {
      width: 100%;
      height: 140px;
      object-fit: cover;
    }

    .game-card h3 {
      margin: 0;
      padding: 1rem;
      font-size: 1.1rem;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #1e1e2f;
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <h1>PlayNow</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Categories</a>
      <a href="#">Top Games</a>
      <a href="#">About</a>
    </nav>
  </header>

  <div class="hero">
    Discover & Play Free Online Games!
  </div>

  <div class="container">
    <h2>Featured Games</h2>
    <div class="game-grid">
      <div class="game-card">
        <img src="https://via.placeholder.com/300x140.png?text=Game+1" alt="Game 1">
        <h3>Speed Racer</h3>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/300x140.png?text=Game+2" alt="Game 2">
        <h3>Block Puzzle</h3>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/300x140.png?text=Game+3" alt="Game 3">
        <h3>Sniper Hero</h3>
      </div>
      <div class="game-card">
        <img src="https://via.placeholder.com/300x140.png?text=Game+4" alt="Game 4">
        <h3>Fruit Slice</h3>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 PlayNow. All rights reserved.
  </footer>

</body>
</html><!-- index.html -->
