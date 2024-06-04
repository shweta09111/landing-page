<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .hero {
      background-image: url('your-image-url');
      background-size: cover;
      background-position: center;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    .hero h1 {
      font-size: 3rem;
    }

    .hero p {
      font-size: 1.2rem;
    }

    .cta {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .cta a {
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      border: 2px solid white;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .cta a:hover {
      background-color: white;
      color: #333;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Your App Name</h1>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Discover the Future of Mobile Apps</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio.</p>
    </div>
  </section>

  <section class="cta">
    <div class="container">
      <a href="#">Download Now</a>
    </div>
  </section>
</body>
</html># landing-page
