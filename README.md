<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nitish Agrawal | CA Finalist</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #ffffff;
      color: #333;
      scroll-behavior: smooth;
    }

    /* Navbar */
    .navbar {
      background-color: #fff;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .navbar-brand {
      font-weight: 600;
      color: #000 !important;
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero img {
      width: 160px;
      height: 160px;
      object-fit: cover;
      border-radius: 50%;
      border: 3px solid #000;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      margin-bottom: 20px;
      transition: transform 0.3s ease;
    }

    .hero img:hover {
      transform: scale(1.05);
    }

    .hero h1 {
      font-size: 1.8rem;
      font-weight: 700;
    }

    .hero h4 {
      font-size: 1.1rem;
      color: #555;
    }

    .hero p {
      color: #666;
    }

    /* Section Titles */
    .section-title {
      text-align: center;
      font-weight: 600;
      margin-bottom: 25px;
    }

    /* Cards */
    .card {
      border: none;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    /* Payment QR */
    .upi-qr {
      max-width: 220px;
      border: 3px solid #000;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    /* Buttons */
    .btn-dark {
      background-color: #000;
      border: none;
      border-radius: 25px;
      padding: 8px 20px;
      transition: background-color 0.3s;
    }

    .btn-dark:hover {
      background-color: #333;
    }

    /* Footer */
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      font-size: 0.9rem;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .hero img {
        width: 140px;
        height: 140px;
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

  <!-- Hero Section -->
  <section class="hero" data-aos="fade-up">
    <img src="profile.jpg" alt="Profile Photo">
    <h1>Nitish Agrawal</h1>
    <h4>CA Finalist</h4>
    <p>Helping clients simplify taxes & compliance</p>
  </section>

  <!-- About Me -->
  <section class="container py-4" data-aos="fade-up">
    <h2 class="section-title">About Me</h2>
    <p class="text-center">
      I am an independent Chartered Accountancy professional offering expert tax filing, GST, and audit services.
      My focus is on providing transparent, timely, and reliable financial solutions tailored to each client’s needs.
    </p>
  </section>

  <!-- Services -->
  <section class="container py-4" data-aos="fade-up">
    <h2 class="section-title">Services Provided</h2>
    <div class="row g-3 text-center">
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <h5>🧾 ITR Filing</h5>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <h5>💰 GST Returns</h5>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <h5>📊 Tax Audit</h5>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card p-3">
          <h5>🏦 Bank Audit</h5>
        </div>
      </div>
    </div>
  </section>

  <!-- Payment Section -->
  <section class="container py-4 text-center" data-aos="fade-up">
    <h2 class="section-title">Payment</h2>
    <img src="phonepayqr.jpg" alt="UPI QR" class="upi-qr">
    <p>Scan using any UPI app (PhonePe, GPay, Paytm)</p>
  </section>

  <!-- Contact -->
  <section class="container py-4 text-center" data-aos="fade-up">
    <h2 class="section-title">Contact</h2>
    <div class="d-grid gap-2 col-8 mx-auto">
      <a href="tel:7828780780" class="btn btn-dark">📞 Call</a>
      <a href="https://wa.me/917828780780" target="_blank" class="btn btn-dark">💬 WhatsApp</a>
      <a href="mailto:nitishagrawal304@gmail.com" class="btn btn-dark">✉️ Email</a>
      <a href="https://maps.app.goo.gl/enh9anWKLChdiq1P8" target="_blank" class="btn btn-dark">📍 View on Map</a>
      <a href="https://instagram.com/nattu.780" target="_blank" class="btn btn-dark">📸 Instagram</a>
      <button onclick="shareCard()" class="btn btn-dark">🔗 Share My Card</button>
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
