<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>qwertyu</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4fff4;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #2e8b57;
      color: white;
      padding: 20px;
      font-size: 28px;
      font-weight: bold;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.2s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      margin-top: 20px;
      padding: 15px;
      background: #2e8b57;
      color: white;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>🌿 qwertyu 🌿</header>

  <div class="gallery">
    <img src= alt="Nature Photo 1">
    <img src="photo2.jpg" alt="Nature Photo 2">
    <img src="" alt="Nature Photo 3">
    <img src="photo4.jpg" alt="Nature Photo 4">
    <img src="photo5.jpg" alt="Nature Photo 5">
    <img src="photo6.jpg" alt="Nature Photo 6">
  </div>

  <footer>© 2025 qwertyu | My Nature Gallery</footer>
</body>
</html>
