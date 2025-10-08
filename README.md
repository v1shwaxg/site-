<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shree Balaji Tractors | Escorts Powertrac & Digitrac Dealer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background: #f8f9fa; color: #222; }

    /* HERO SECTION */
    header {
      position: relative;
      background: url('index.html/staff.jpg.jpeg') center/cover no-repeat;
      height: 95vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      color: white;
      overflow: hidden;
    }
    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0; width: 100%; height: 100%;
      background: rgba(0,0,0,0.55);
      z-index: 1;
    }
    .hero-content {
      position: relative;
      z-index: 2;
      padding: 20px;
      animation: fadeIn 1.5s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .hero-logo {
      width: 120px;
      border-radius: 50%;
      box-shadow: 0 0 20px rgba(255,255,255,0.4);
      margin-bottom: 15px;
    }
    .hero-title {
      font-size: 2.6rem;
      font-weight: 700;
      text-shadow: 0 0 10px rgba(0,0,0,0.6);
    }
    .hero-subtitle {
      font-size: 1.1rem;
      color: #ffeb3b;
      margin-bottom: 25px;
    }
    .buttons {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }
    .btn {
      background: #1b5e20;
      color: #fff;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }
    .btn:hover { background: #43a047; transform: scale(1.05); }
    .btn.whatsapp { background: #25D366; }
    .btn.whatsapp:hover { background: #1ebf5d; }

    /* SECTION STYLES */
    section { padding: 60px 10%; background: #fff; }
    section:nth-child(even) { background: #f3f3f3; }
    .section-title {
      text-align: center;
      font-size: 1.9rem;
      font-weight: 700;
      margin-bottom: 40px;
      color: #1b5e20;
    }

    /* FOUNDER */
    .founder {
      display: flex;
      align-items: center;
      flex-wrap: wrap;
      justify-content: center;
      gap: 40px;
    }
    .founder img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #1b5e20;
    }
    .founder-text {
      max-width: 500px;
      font-size: 1rem;
      line-height: 1.6;
    }

    /* TRACTOR SHOWCASE */
    .tractors {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      text-align: center;
    }
    .tractor-card {
      background: white;
      border-radius: 15px;
      padding: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .tractor-card:hover { transform: translateY(-5px); }
    .tractor-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 12px;
    }
    .tractor-card h3 { color: #1b5e20; margin-top: 10px; }

    /* CONTACT */
    .contact-info {
      text-align: center;
      line-height: 1.8;
      font-size: 1.05rem;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      margin-top: 20px;
      border-radius: 10px;
    }

    /* FOOTER */
    footer {
      background: #1b5e20;
      color: #fff;
      text-align: center;
      padding: 25px 10px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <div class="hero-content">
      <img src="index.html/logo_shreebalaji.png.jpeg" alt="Agency Logo" class="hero-logo" />
      <h1 class="hero-title">Shree Balaji Tractors</h1>
      <p class="hero-subtitle">Authorised Dealer - Escorts Powertrac & Digitrac</p>
      <div class="buttons">
        <a href="tel:9045452080" class="btn">📞 Call Now</a>
        <a href="https://wa.me/919045452080?text=Hello%20Shree%20Balaji%20Tractors!%20I%20am%20interested%20in%20your%20tractors." class="btn whatsapp">💬 WhatsApp Now</a>
      </div>
    </div>
  </header>

  <!-- FOUNDER -->
  <section>
    <h2 class="section-title">Founder & Director</h2>
    <div class="founder">
      <img src="index.html/founder.jpg.jpeg" alt="Founder">
      <div class="founder-text">
        <h3>Dr. Vikas Chandra Gupta (Ph.D., D.Litt.)</h3>
        <p>Founder of <b>Shree Balaji Tractors</b>, Dr. Vikas Chandra Gupta has over 25 years of experience empowering farmers with reliable tractors, genuine parts, and expert service. Under his leadership, we have grown as a trusted name in the agricultural sector.</p>
      </div>
    </div>
  </section>

  <!-- TRACTOR SHOWCASE -->
  <section>
    <h2 class="section-title">Our Tractor Range</h2>
    <div class="tractors">
      <div class="tractor-card">
        <img src="index.html/euroseriestractor.jgp.webp" alt="Powertrac Euro Series">
        <h3>Powertrac Euro Series</h3>
        <p>High-performance tractors built for reliability and power.</p>
      </div>
      <div class="tractor-card">
        <img src="index.html/rdx.jpg" alt="RDX Series">
        <h3>Powertrac RDX Series</h3>
        <p>Affordable and efficient – ideal for versatile farming tasks.</p>
      </div>
      <div class="tractor-card">
        <img src="index.html/digitrac.jpg" alt="Digitrac Series">
        <h3>Digitrac Series</h3>
        <p>Smart, connected tractors designed with modern technology.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section>
    <h2 class="section-title">Contact & Location</h2>
    <div class="contact-info">
      <p><b>📍 Address:</b> Shree Ganesh Colony, in front of Raj Cold Storage, Amanpur Road, Kasganj, 207123</p>
      <p><b>📞 Phone:</b> 9045452080</p>
      <p><b>✉️ Email:</b> vikaschandragupta59@gmail.com</p>
      <iframe src="https://www.google.com/maps?q=Shree+Balaji+Tractors,+Kasganj&output=embed"></iframe>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2025 Shree Balaji Tractors | Escorts Powertrac & Digitrac Dealer</p>
    <p>Website Designed by <b>Vishwas Gupta</b></p>
  </footer>

</body>
</html>
