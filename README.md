<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile App Landing Page</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Open Sans', sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

h1, h2, h3, h4, h5, h6 {
  font-weight: 700;
  color: #212121;
}

p {
  font-size: 16px;
  margin-bottom: 20px;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

li {
  margin-bottom: 20px;
}

a {
  text-decoration: none;
  color: #337ab7;
}

a:hover {
  color: #23527c;
}

button {
  border: none;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}

button.primary {
  background-color: #337ab7;
  color: #fff;
}

button.secondary {
  background-color: #f7f7f7;
  color: #333;
  border: 1px solid #ddd;
}

button:hover {
  opacity: 0.8;
}

/* Container */

.container {
  max-width: 1200px;
  margin: 40px auto;
  padding: 20px;
}

/* Hero Section */

.hero {
  background-color: #337ab7;
  color: #fff;
  padding: 40px;
  text-align: center;
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

.hero button {
  margin-top: 20px;
}

/* Features Section */

.features {
  background-color: #f9f9f9;
  padding: 40px;
}

.features ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.features li {
  width: 30%;
  margin: 20px;
  text-align: center;
}

.features i {
  font-size: 36px;
  margin-bottom: 10px;
}

/* Screenshots Section */

.screenshots {
  background-color: #f9f9f9;
  padding: 40px;
}

.screenshots.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.screenshots img {
  width: 30%;
  margin: 20px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Testimonials Section */

.testimonials {
  background-color: #f9f9f9;
  padding: 40px;
}

.testimonials ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.testimonials li {
  width: 30%;
  margin: 20px;
  text-align: center;
}

.testimonials span {
  font-size: 16px;
  color: #337ab7;
}

/* Pricing Plans Section */

.pricing {
  background-color: #f9f9f9;
  padding: 40px;
}

.pricing ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.pricing li {
  width: 30%;
  margin: 20px;
  text-align: center;
  border: 1px solid #ddd;
  padding: 20px;
}

.pricing h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.pricing p {
  font-size: 18px;
  margin-bottom: 20px;
}

.pricing ul li ul {
  list-style: disc;
  padding: 10px;
}

/* Contact Section */

.contact {
  background-color: #f9f9f9;
  padding: 40px;
}

.contact form {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.contact input,.contact textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
}

.contact button {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
}

/* Responsive Design */

@media (max-width: 768px) {
 .container {
    max-width: 90%;
  }
 .features ul {
    flex-direction: column;
  }
 .features li {
    width: 100%;
    margin: 20px 0;
  }
 .screenshots.gallery {
    flex-direction: column;
  }
 .screenshots img {
    width: 100%;
    margin: 20px 0;
  }
 .testimonials ul {
    flex-direction: column;
  }
 .testimonials li {
    width: 100%;
    margin: 20px 0;
  }
 .pricing ul {
    flex-direction: column;
  }
 .pricing li {
    width: 100%;
    margin: 20px 0;
  }
 .contact form {
    flex-direction: column;
  }
}
</style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Introducing AppName</h1>
            <p>Experience the future of mobile apps</p>
            <button class="btn primary">Download Now</button>
            <button class="btn secondary">Learn More</button>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="container">
            <h2>What makes AppName special?</h2>
            <ul>
                <li>
                    <i class="icon-feature-1"></i>
                    <h3>Feature 1</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </li>
                <li>
                    <i class="icon-feature-2"></i>
                    <h3>Feature 2</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </li>
                <li>
                    <i class="icon-feature-3"></i>
                    <h3>Feature 3</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </li>
            </ul>
        </div>
    </section>

    <!-- Screenshots Section -->
    <section class="screenshots">
        <div class="container">
            <h2>See AppName in action</h2>
            <div class="gallery">
                <img src="screenshot-1.png" alt="Screenshot 1">
                <img src="screenshot-2.png" alt="Screenshot 2">
                <img src="screenshot-3.png" alt="Screenshot 3">
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <h2>What our users say</h2>
            <ul>
                <li>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <span>John Doe</span>
                </li>
                <li>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <span>Jane Doe</span>
                </li>
                <li>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <span>Bob Smith</span>
                </li>
            </ul>
        </div>
    </section>

    <!-- Pricing Plans Section -->
    <section class="pricing">
        <div class="container">
            <h2>Choose your plan</h2>
            <ul>
                <li>
                    <h3>Basic</h3>
                    <p>$9.99/month</p>
                    <ul>
                        <li>Feature 1</li>
                        <li>Feature 2</li>
                    </ul>
                </li>
                <li>
                    <h3>Premium</h3>
                    <p>$19.99/month</p>
                    <ul>
                        <li>Feature 1</li>
                        <li>Feature 2</li>
                        <li>Feature 3</li>
                    </ul>
                </li>
            </ul>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <div class="container">
            <h2>Get in touch</h2>
            <form>
                <input type="email" placeholder="Email">
                <textarea placeholder="Message"></textarea>
                <button class="btn primary">Send</button>
            </form>
            <p>Or download the app directly:</p>
            <button class="btn secondary">Download Now</button>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
