<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sande Tech Solutions</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #000;
      color: #fff;
      text-align: center;
    }

    header {
      padding: 50px 20px;
      background: linear-gradient(90deg, #0f0f0f, #1a1a1a);
      box-shadow: 0 0 20px #8e44ad;
    }

    header h1 {
      font-size: 3em;
      color: #8e44ad;
      text-shadow: 0 0 10px #9b59b6, 0 0 20px #6c3483;
    }

    .services {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 40px;
      padding: 50px 20px;
    }

    .service {
      background-color: #111;
      border: 2px solid #8e44ad;
      border-radius: 15px;
      width: 200px;
      height: 200px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.5em;
      cursor: pointer;
      transition: 0.3s;
      box-shadow: 0 0 20px #8e44ad;
    }

    .service:hover {
      background-color: #1a1a1a;
      transform: scale(1.1);
      box-shadow: 0 0 40px #9b59b6, 0 0 60px #6c3483;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    footer {
      padding: 20px;
      background-color: #111;
      border-top: 2px solid #8e44ad;
      color: #8e44ad;
      text-shadow: 0 0 10px #6c3483;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sande Tech Solutions</h1>
  </header>

  <div class="services">
    <div class="service">
      <a href="games.html">Games</a>
    </div>
    <div class="service">
      <a href="music.html">Music</a>
    </div>
    <div class="service">
      <a href="movies.html">Movies & Series</a>
    </div>
  </div>

  <footer>
    &copy; 2025 Sande Tech Solutions
  </footer>

</body>
</html>
