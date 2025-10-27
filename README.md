<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nitish Agrawal | CA Finalist</title>
  <link rel="icon" href="profile.jpg" type="image/jpg" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f8f9fa;
      color: #333;
      scroll-behavior: smooth;
    }

    /* Navbar */
    .navbar {
      background-color: white;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .navbar-brand {
      color: #0056b3 !important;
      font-weight: 600;
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 70px 20px 50px;
      background-color: #fff;
    }

    .hero img {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #0056b3;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      margin-bottom: 20px;
      transition: transform 0.3s ease-in-out;
    }

    .hero img:hover {
      transform: scale(1.05);
    }

    .hero h1 {
      font-size: 1.8rem;
      font-weight: 700;
      color: #0056b3;
    }

    .hero h4 {
      font-size: 1.1rem;
      color: #555;
    }

    .hero p {
      font-size: 0.95rem;
      color: #777;
    }

    /* Section Titles */
    .section-title {
      text-align: center;
      color: #0056b3;
      font-weight: 600;
      margin-bottom: 20px;
      font-size: 1.4rem;
    }

    /* Cards & Services */
    .service-icon {
      font-size: 2rem;
      color: #0056b3;
      margin-bottom: 10px;
    }

    .card {
      border: none;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    /* Payment */
    .upi-qr {
      max-width: 240px;
      border: 4px solid #0056b3;
      border-radius: 15px;
      margin-bottom: 10px;
    }

    .btn-primary {
      background-color: #0056b3;
      border: none;
      border-radius: 25px;
      padding: 8px 20px;
    }

    .btn-primary:hover {
      background-color: #003f88;
    }

    /* Footer */
    footer {
      background-color: #0056b3;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 40px;
      font-size: 0.9rem;
    }

    @media (max-width: 768px) {
      .hero img {
        width: 150px;
        height: 150px;
      }
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-light sticky-top">
    <div class="container">
      <a class="navbar-brand mx-auto" href="#">Nitish Agrawal</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero" data-aos="fade-up">
    <img src="profile.jpg" alt="Profile Photo">
    <h1>Nitish Agrawal</h1>
    <h4>CA Finalist</h4>
    <p>Helping clients simplify taxes & compliance</p>
  </section>

  <!-- About -->
  <section class="container py-4" id="about" data-aos="fade-up">
    <h2 class="section-title">About Me</h2>
    <p class="text-center">
      I am an independent Chartered Accountancy professional dedicated to helping individuals and businesses
      manage taxation, GST, and audit services with transparency and precision.  
      My goal is to simplify financial processes and build long-term trust with every client.
    </p>
  </section>

  <!-- Business Ventures -->
  <section class="container py-4" id="ventures" data-aos="fade-up">
    <h2 class="section-title">My Business Ventures</h2>
    <div class="row g-3">
      <div class="col-md-4 col-12">
        <div class="card text-center p-3">
          <div class="service-icon">👕</div>
          <h5>Poonam Kapda Dukan</h5>
          <p>Textile & Garments</p>
        </div>
      </div>
      <div class="col-md-4 col-12">
        <div class="card text-center p-3">
          <div class="service-icon">🍽️</div>
          <h5>Poonam Bartan Dukan</h5>
          <p>Household Utensils & Kitchenware</p>
        </div>
      </div>
      <div class="col-md-4 col-12">
        <div class="card text-center p-3">
          <div class="service-icon">🌾</div>
          <h5>Poonam Krishi Sewa Kendra</h5>
          <p>Agricultural Tools & Services</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section class="container py-4" id="services" data-aos="fade-up">
    <h2 class="section-title">Services Provided</h2>
    <div class="row text-center g-3">
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <div class="service-icon">🧾</div>
          <h6>ITR Filing</h6>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <div class="service-icon">💰</div>
          <h6>GST Returns</h6>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <div class="service-icon">📊</div>
          <h6>Tax Audit</h6>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <div class="service-icon">🏦</div>
          <h6>Bank Audit</h6>
        </div>
      </div>
    </div>
  </section>

  <!-- Payment Section -->
  <section class="container py-4 text-center" id="payment" data-aos="fade-up">
    <h2 class="section-title">Payment</h2>
    <img src="phonepayqr.jpg" class="upi-qr" alt="UPI QR">
    <p>Scan using any UPI app (PhonePe, GPay, Paytm)</p>
    <a href="phonepayqr.jpg" download class="btn btn-primary">Download UPI QR</a>
  </section>

  <!-- Contact Section -->
  <section class="container py-4 text-center" id="contact" data-aos="fade-up">
    <h2 class="section-title">Contact</h2>
    <div class="d-grid gap-2 col-8 mx-auto">
      <a href="tel:7828780780" class="btn btn-primary">📞 Call</a>
      <a href="https://wa.me/917828780780" target="_blank" class="btn btn-primary">💬 WhatsApp</a>
      <a href="mailto:nitishagrawal304@gmail.com" class="btn btn-primary">✉️ Email</a>
      <a href="https://maps.app.goo.gl/enh9anWKLChdiq1P8" target="_blank" class="btn btn-primary">📍 View on Map</a>
      <a href="https://instagram.com/nattu.780" target="_blank" class="btn btn-primary">📸 Instagram</a>
      <button onclick="shareCard()" class="btn btn-primary">🔗 Share My Card</button>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 Nitish Agrawal — All Rights Reserved
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 800, once: true });

    function shareCard() {
      if (navigator.share) {
        navigator.share({
          title: 'Nitish Agrawal | CA Finalist',
          text: 'Check out Nitish Agrawal’s professional profile',
          url: window.location.href
        });
      } else {
        alert("Sharing not supported on this browser.");
      }
    }
  </script>
</body>
</html>
