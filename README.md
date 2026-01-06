# Nakimera-Skin-Care
Platform which provides all kinds of cosmetics products
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Nakimera Skin Care Solutions</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <!-- SEO -->
  <meta name="description" content="Nakimera Skin Care Solutions offers high-quality cosmetics and skin care products for all skin types worldwide." />
  <meta name="keywords" content="cosmetics, skincare, beauty products, global skincare" />

  <!-- React CDN -->
  <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #ffffff;
      color: #333;
    }

    header {
      background: #111;
      color: #fff;
      padding: 20px;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: auto;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }

    .hero {
      background: linear-gradient(to right, #f4c2d7, #fde6ef);
      padding: 90px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 2.8rem;
    }

    .hero p {
      max-width: 650px;
      margin: 20px auto;
      font-size: 1.1rem;
    }

    .btn {
      background: #111;
      color: #fff;
      padding: 14px 32px;
      border: none;
      cursor: pointer;
      margin-top: 20px;
      border-radius: 4px;
      font-size: 1rem;
    }

    .section {
      padding: 80px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .section h2 {
      text-align: center;
      margin-bottom: 50px;
      font-size: 2.2rem;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 25px;
    }

    .card {
      border: 1px solid #eee;
      padding: 30px;
      border-radius: 6px;
      text-align: center;
      background: #fff;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .trust {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 30px;
      text-align: center;
    }

    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 25px;
      margin-top: 60px;
      font-size: 0.9rem;
    }

    .order {
      text-align: center;
      margin-top: 40px;
    }

    .order a {
      display: inline-block;
      margin: 10px;
      color: #111;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <div id="root"></div>

  <script type="text/babel">
    function App() {
      return (
        <>
          <header>
            <nav>
              <h2>Nakimera</h2>
              <div>
                <a href="#products">Products</a>
                <a href="#about">About</a>
                <a href="#order">Order</a>
              </div>
            </nav>
          </header>

          <section className="hero">
            <h1>Global Skin Care, Designed for You</h1>
            <p>
              Nakimera Skin Care Solutions delivers premium cosmetic and skin care
              products crafted for all skin types, tones, and regions worldwide.
            </p>
            <button className="btn">Explore Products</button>
          </section>

          <section id="products" className="section">
            <h2>Our Product Categories</h2>
            <div className="products">
              <div className="card">
                <h3>Facial Care</h3>
                <p>Cleansers, serums, toners, moisturizers</p>
              </div>
              <div className="card">
                <h3>Body Care</h3>
                <p>Lotions, oils, scrubs, soaps</p>
              </div>
              <div className="card">
                <h3>Make-Up</h3>
                <p>Foundations, lip products, eye cosmetics</p>
              </div>
              <div className="card">
                <h3>Hair Care</h3>
                <p>Shampoos, conditioners, treatments</p>
              </div>
            </div>
          </section>

          <section id="about" className="section">
            <h2>Why Nakimera</h2>
            <div className="trust">
              <div>
                <h3>Dermatology-Inspired</h3>
                <p>Formulations guided by modern skin science.</p>
              </div>
              <div>
                <h3>Global Standards</h3>
                <p>Products sourced and tested to meet international quality expectations.</p>
              </div>
              <div>
                <h3>Inclusive Beauty</h3>
                <p>Suitable for all skin tones, genders, and regions.</p>
              </div>
            </div>
          </section>

          <section id="order" className="section order">
            <h2>Order Worldwide</h2>
            <p>We accept global orders through WhatsApp and email.</p>

            <a href="https://wa.me/0000000000" target="_blank">Order via WhatsApp</a>
            <a href="mailto:orders@nakimeraskincare.com">Order via Email</a>
          </section>

          <footer>
            © 2026 Nakimera Skin Care Solutions · Worldwide Shipping Available
          </footer>
        </>
      );
    }

    ReactDOM.createRoot(document.getElementById("root")).render(<App />);
  </script>
</body>
</html>
