<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Based Shops - Your one-stop destination for fishing gear, cannabis accessories, and underground music gear." />
  <meta name="keywords" content="Fishing Gear, Cannabis Accessories, Music, Underground Music, Shop" />
  <meta property="og:title" content="Based Shops" />
  <meta property="og:description" content="Explore our unique collection of gear, accessories, and music." />
  <meta property="og:image" content="path-to-your-image.jpg" />
  <meta property="og:url" content="https://basedshops.com" />
  <title>Based Shops</title>

  <!-- Preconnect links for performance -->
  <link rel="preconnect" href="https://cdnjs.cloudflare.com">
  <link rel="preconnect" href="https://fonts.googleapis.com">

  <!-- FontAwesome & Google Fonts -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-oBwL+hZUnDPdhjK2DTTXQ1f8LhG4N2mXKoPd+kP4EfykJ7CvjPhxzEtHkLBVbFr+6HXeJ2Y6LbyztC4cZ7z0vQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #3b3a2f;
      /* Dark brown background for a natural feel */
      color: #e4e4d9;
      /* Light tan for text */
    }

    header {
      background: linear-gradient(135deg, #3e4b3d, #6a7a54);
      /* Camouflage greens */
      padding: 2rem 1rem;
      text-align: center;
      border-bottom: 4px solid #8a9a5b;
      /* Light olive green border */
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
    }

    .logo {
      max-width: 100px;
      /* Logo optimization */
      margin-bottom: 1rem;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      color: #d4d08c;
      /* Light olive yellow */
      letter-spacing: 2px;
      text-shadow: 2px 2px #1a1a1a;
      /* Darker shadow for readability */
      transition: color 0.3s ease-in-out;
    }

    header h1:hover {
      color: #f1e48f;
      /* Lighter yellow when hovered */
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      color: #b4b08d;
      /* Light greenish-beige */
      margin: 0 1.5rem;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1rem;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #f1f1f1;
      /* Light grayish white for hover effect */
    }

    .container {
      padding: 2rem 1rem;
      max-width: 960px;
      margin: auto;
    }

    .section {
      background: #555441;
      /* Muted brown-green background for sections */
      border: 2px solid #7c7f5f;
      /* Slightly lighter border */
      padding: 2rem;
      margin-bottom: 2rem;
      border-radius: 1rem;
      box-shadow: 0 0 20px rgba(0, 255, 120, 0.05);
    }

    .section h2 {
      color: #b4b08d;
      /* Matching greenish-beige color */
      font-size: 2rem;
      margin-bottom: 1rem;
      transition: color 0.3s ease-in-out;
    }

    .section h2:hover {
      color: #f1e48f;
      /* Light yellow for hover effect */
    }

    .section p,
    .section a {
      font-size: 1rem;
      line-height: 1.8;
      color: #d4d08c;
      /* Light olive yellow for text */
    }

    .section a:hover {
      color: #f1f1f1;
      /* Light grayish white on hover */
    }

    .social {
      margin-top: 1rem;
    }

    .social a {
      color: #b4b08d;
      /* Light greenish-beige */
      display: inline-block;
      margin-right: 1.5rem;
      font-size: 1.4rem;
      transition: color 0.3s ease-in-out;
    }

    .social a:hover {
      color: #f1f1f1;
      /* Hover color */
    }

    .social i {
      margin-right: 0.5rem;
    }

    footer {
      background: #3b3a2f;
      /* Dark brown to match the body */
      padding: 1rem;
      text-align: center;
      font-size: 0.9rem;
      color: #888;
      border-top: 1px solid #6a7a54;
      /* Olive green border */
    }

    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 0.5rem 0;
      }

      /* Mobile Navigation Menu */
      .menu-toggle {
        display: block;
        cursor: pointer;
        font-size: 1.5rem;
        color: #b4b08d;
      }

      .nav-links {
        display: none;
        flex-direction: column;
      }

      .nav-links.active {
        display: flex;
      }

      nav a {
        margin: 0;
      }
    }
  </style>
</head>

<body>

  <header>
    <img src="Screenshot 2025-04-08 170604.png" alt="Based Shops Logo" class="logo">
    <h1>Based Shops</h1>
    <div class="menu-toggle" onclick="toggleMenu()">☰</div>
    <nav>
      <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <div class="container">
    <section id="home" class="section">
      <h2>Welcome to Based Shops</h2>
      <p>Yo! Looking for fishing gear, cannabis accessories (gear only), or exclusive underground music? Based Shops has your back. We keep it real for those who vibe with nature, beats, and chill gear.</p>
    </section>

    <section id="about" class="section">
      <h2>About Us</h2>
      <p>Based Shops is built for the next-gen explorers and creators. Whether you're setting hooks or spinning records, our collection is inspired by freedom, nature, and the underground scene. We’re all about good gear, real people, and doing it your way.</p>
    </section>
    <section id="contact" class="section">
      <h2>Contact</h2>
      <p>Hit us up anytime: <a href="mailto:basedshops@gmail.com">basedshops@gmail.com</a></p>
      <div class="social">
        <p>Connect with us:</p>
        <a href="https://www.facebook.com/marketplace/profile" target="_blank"><i class="fab fa-facebook"></i>Facebook</a>
        <a href="https://www.instagram.com/ruggedvibesco" target="_blank"><i class="fab fa-instagram"></i>Instagram</a>
      </div>
    </section>
  </div>

  <footer>
    &copy; 2025 Based Shops. All rights reserved.
  </footer>

  <script>
    function toggleMenu() {
      const navLinks = document.querySelector('.nav-links');
      navLinks.classList.toggle('active');
    }
  </script>

</body>

</html>
