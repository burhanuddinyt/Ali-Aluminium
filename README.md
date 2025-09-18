<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ali Aluminium Works</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #005c97, #363795);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1100px;
      margin: auto;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    .contact {
      text-align: center;
      background: #005c97;
      color: white;
      padding: 2rem 1rem;
      border-radius: 10px;
    }
    .contact h2 {
      margin-top: 0;
    }
    footer {
      text-align: center;
      background: #222;
      color: #aaa;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ali Aluminium Works</h1>
    <p>Aluminium Sections • Doors • Sliding Windows</p>
  </header>

  <section>
    <h2>About Us</h2>
    <p>
      Welcome to Ali Aluminium Works. We specialize in high-quality aluminium 
      sections, doors, and sliding windows. With years of experience, 
      we provide durable, stylish, and affordable solutions for homes and businesses.
    </p>
  </section>

  <section>
    <h2>Our Work</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" alt="Aluminium Door">
      <img src="https://images.unsplash.com/photo-1560184897-ae75f4184934" alt="Sliding Window">
      <img src="https://images.unsplash.com/photo-1628744894984-1f3b0a7b5e67" alt="Aluminium Frame">
      <img src="https://images.unsplash.com/photo-1598300056427-c4a5d82a65fa" alt="Modern Aluminium Design">
    </div>
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <p>📞 +91 74892 53290</p>
    <p>📍 850, Khati wala Tank
            Transport Nagar
            Main Road, INDORE (M.P)</p>
  </section>

  <footer>
    <p>&copy; 2025 Ali Aluminium Works. All rights reserved.</p>
  </footer>
</body>
</html>
