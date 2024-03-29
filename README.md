<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 10px 20px;
      margin: 0 10px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    nav a:hover {
      background-color: #555;
    }
    .container {
      max-width: 960px;
      margin: 20px auto;
      padding: 0 20px;
    }
    h1 {
      text-align: center;
    }
    .portfolio-item {
      background-color: #fff;
      border-radius: 5px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .portfolio-item:hover {
      transform: translateY(-5px);
    }
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
    .animated {
      animation: fadeIn 1s ease-in-out;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Portfolio</a>
      <a href="#">Contact</a>
    </nav>
  </header>
  <div class="container">
    <div class="portfolio-item animated">
      <h2>Project 1</h2>
      <p>This is a description of Project 1.</p>
    </div>
    <div class="portfolio-item animated" style="animation-delay: 0.3s;">
      <h2>Project 2</h2>
      <p>This is a description of Project 2.</p>
    </div>
    <div class="portfolio-item animated" style="animation-delay: 0.6s;">
      <h2>Project 3</h2>
      <p>This is a description of Project 3.</p>
    </div>
  </div>
</body>
</html>
