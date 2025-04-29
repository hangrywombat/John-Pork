<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff7f4;
      color: #4a3f35;
    }
    header {
      background-color: #f8c8dc;
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #4a3f35;
      font-weight: bold;
    }
    .content {
      padding: 40px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    .featured-image {
      text-align: center;
      margin-bottom: 30px;
    }
    .featured-image img {
      max-width: 300px;
      border-radius: 15px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #f8c8dc;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <section id="home" class="content">
    <h2>Home</h2>
    <p>Hello! I'm glad you're here. This is my personal portfolio showcasing who I am and what I do.</p>
  </section>

  <section id="about" class="content">
    <h2>About Me</h2>
    <div class="featured-image">
      <img src="https://raw.githubusercontent.com/your-username/your-repo-name/main/images/john_pork.png" alt="John Pork">
      <p>This is John Pork — always stylish, always calling.</p>
    </div>
    <p>Here's a little about me and a gallery of things I love or have worked on.</p>
    <p>Caleb D. and Aidan N. are interesting fellows.</p>
    <div class="gallery">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 1">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 2">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 3">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 My Portfolio</p>
  </footer>
</body>
</html>
