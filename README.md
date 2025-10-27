<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nitish Agrawal | Vaada & Associates</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-color: #f8f9fa;
      color: #333;
      scroll-behavior: smooth;
    }

    .navbar {
      background-color: #ffffff;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .navbar-brand {
      font-weight: 600;
      color: #555 !important;
    }

    .hero {
      text-align: center;
      padding: 120px 20px 60px;
      background: linear-gradient(to bottom, #ffffff, #f4f4f4);
    }

    .hero img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid silver;
      margin-bottom: 25px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.15);
    }

    .hero h1 {
      font-size: 2.4rem;
      font-weight: 700;
    }

    .hero h5 {
      color: #777;
      font-weight: 500;
    }

    .hero p {
      color: #555;
    }

    .section-title {
      font-weight: 600;
      text-align: center;
      margin-bottom: 30px;
      color: #333;
    }

    .service-card {
      background: white;
      border: 1px solid #e5e5e5;
      border-radius: 12px;
      padding: 25px;
      text-align: center;
      transition: all 0.3s ease;
    }

    .service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 16px rgba(0,0,0,0.1);
    }

    .contact-info {
      background-color: #ffffff;
      border-radius: 12px;
      padding: 30px;
      text-align: center;
      border: 1px solid #e5e5e5;
    }

    .btn-silver {
      background-color: silver;
      color: black;
      border-radius: 25px;
      padding: 10px 20px;
      transition: all 0.3s;
    }

    .btn-silver:hover {
      background-color: #b0b0b0;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #f0f0f0;
      font-size: 0.9rem;
      color: #555;
      margin-top: 50px;
    }

    .qr-img {
      width: 150px;
      height: 150px;
      border-radius: 8px;
      border: 1px solid #ddd;
      object-fit: cover;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Nitish Agrawal</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero" id="home" data-aos="fade-up">
    <img src="profile.jpg" alt="Profile Photo">
    <h1>Nitish Agrawal</h1>
    <h5>CA Finalist | Vaada & Associates</h5>
    <p>Helping clients simplify taxes & compliance</p>
    <div class="mt-3">
      <a href="tel:7828780780" class="btn btn-silver me-2">📞 Call</a>
      <a href="https://wa.me/917828780780" class="btn btn-silver me-2">💬 WhatsApp</a>
      <a href="mailto:nitishagrawal304@gmail.com" class="btn btn-silver me-2">✉️ Email</a>
      <a href="https://www.instagram.com/nattu.780" class="btn btn-silver me-2">📸 Instagram</a>
      <button class="btn btn-silver" onclick="shareCard()">📤 Share My Card</button>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="container my-5" data-aos="fade-up">
    <h2 class="section-title">About Me</h2>
    <p class="text-center">
      I’m <strong>Nitish Agrawal</strong>, a CA Finalist and partner at <strong>Vaada & Associates</strong>.  
      Our firm provides professional services in taxation, GST, and audits for individuals and businesses.
      <br><br>
      Apart from my professional practice, I also manage multiple business ventures in Saraipali:
    </p>
    <ul class="text-center list-unstyled">
      <li>🧵 Poonam Kapda Dukan</li>
      <li>🍽️ Poonam Bartan Dukan</li>
      <li>🌾 Poonam Krishi Sewa Kendra</li>
    </ul>
  </section>

  <!-- Services -->
  <section id="services" class="container my-5" data-aos="fade-up">
    <h2 class="section-title">Our Services</h2>
    <div class="row g-4">
      <div class="col-md-3">
        <div class="service-card">
          <h5>ITR Filing</h5>
          <p>Accurate and on-time income tax return filing for individuals and businesses.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="service-card">
          <h5>GST Returns</h5>
          <p>Monthly and annual GST compliance services with expert support.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="service-card">
          <h5>Tax Audit</h5>
          <p>Professional audit and tax verification services to ensure compliance.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="service-card">
          <h5>Bank Audit</h5>
          <p>Comprehensive auditing solutions for banks and financial institutions.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="container my-5" data-aos="fade-up">
    <h2 class="section-title">Contact</h2>
    <div class="contact-info mx-auto" style="max-width: 600px;">
      <p><strong>Phone:</strong> <a href="tel:7828780780">7828780780</a></p>
      <p><strong>Email:</strong> <a href="mailto:nitishagrawal304@gmail.com">nitishagrawal304@gmail.com</a></p>
      <p>
        <strong>Address:</strong> 
        <a href="https://maps.app.goo.gl/enh9anWKLChdiq1P8" target="_blank">
          Baloda, Saraipali, Mahasamund, C.G. 493558 📍
        </a>
      </p>
      <img src="phonepayqr.jpg" alt="UPI QR" class="qr-img">
      <div class="mt-3">
        <a href="upi://pay?pa=7828780780@upi&pn=Nitish%20Agrawal" class="btn btn-silver">💰 Pay via UPI</a>
      </div>
    </div>
  </section>

  <footer>
    © 2025 Vaada & Associates | Designed by Nitish Agrawal
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 700, once: true });

    function shareCard() {
      if (navigator.share) {
        navigator.share({
          title: 'Nitish Agrawal | Vaada & Associates',
          text: 'Check out Nitish Agrawal’s professional profile and services.',
          url: window.location.href
        });
      } else {
        navigator.clipboard.writeText(window.location.href);
        alert('Link copied! You can share it manually.');
      }
    }
  </script>
</body>
</html>
