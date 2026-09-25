<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anurag Digital Media</title>
  <meta name="description" content="Anurag Digital Media - Digital Media, Artist Verification and Promotion">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0b0b0f;
      color: #fff;
      line-height: 1.6;
    }

    header {
      padding: 20px 7%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #111116;
      border-bottom: 1px solid #292933;
    }

    .logo {
      font-size: 22px;
      font-weight: 800;
      letter-spacing: .5px;
    }

    .logo span {
      color: #ff3158;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 22px;
      font-size: 14px;
    }

    nav a:hover {
      color: #ff3158;
    }

    .hero {
      min-height: 78vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 70px 20px;
      background:
        radial-gradient(circle at top, #321322 0%, #0b0b0f 55%);
    }

    .hero-content {
      max-width: 850px;
    }

    .badge {
      display: inline-block;
      padding: 8px 16px;
      border: 1px solid #ff3158;
      border-radius: 30px;
      color: #ff6b86;
      font-size: 13px;
      margin-bottom: 22px;
    }

    h1 {
      font-size: clamp(42px, 8vw, 82px);
      line-height: 1.05;
      margin-bottom: 22px;
    }

    h1 span {
      color: #ff3158;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      color: #bdbdc7;
      font-size: 18px;
    }

    .buttons {
      margin-top: 35px;
    }

    .btn {
      display: inline-block;
      padding: 14px 25px;
      margin: 7px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .primary {
      background: #ff3158;
      color: white;
    }

    .secondary {
      border: 1px solid #555563;
      color: white;
    }

    section {
      padding: 75px 7%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 45px;
    }

    .section-title h2 {
      font-size: 38px;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #aaaab5;
    }

    .cards {
      max-width: 1100px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: #15151c;
      border: 1px solid #292933;
      padding: 30px;
      border-radius: 15px;
    }

    .icon {
      font-size: 32px;
      margin-bottom: 18px;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card p {
      color: #aaaab5;
      font-size: 15px;
    }

    .verification {
      background: #111116;
      text-align: center;
    }

    .verify-box {
      max-width: 800px;
      margin: auto;
      background: #181820;
      padding: 45px 25px;
      border-radius: 18px;
      border: 1px solid #30303b;
    }

    .verify-box p {
      color: #bdbdc7;
      margin: 15px auto 25px;
    }

    .contact {
      text-align: center;
    }

    .contact-info {
      margin-top: 25px;
      font-size: 18px;
    }

    .contact-info a {
      color: #ff6b86;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #07070a;
      color: #777783;
      font-size: 13px;
    }

    @media (max-width: 750px) {
      header {
        flex-direction: column;
        gap: 15px;
      }

      nav a {
        margin: 0 7px;
      }

      .cards {
        grid-template-columns: 1fr;
      }

      section {
        padding: 55px 5%;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="logo">Anurag <span>Digital Media</span></div>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#verification">Verification</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

<section class="hero" id="home">
  <div class="hero-content">
    <div class="badge">DIGITAL MEDIA & ARTIST SERVICES</div>

    <h1>
      Your Talent.<br>
      <span>Your Digital Identity.</span>
    </h1>

    <p>
      Anurag Digital Media helps artists, creators and digital talent
      build a professional online presence and get verified.
    </p>

    <div class="buttons">
      <a class="btn primary" href="#verification">Artist Verification</a>
      <a class="btn secondary" href="#contact">Contact Us</a>
    </div>
  </div>
</section>

<section id="services">
  <div class="section-title">
    <h2>Our Services</h2>
    <p>Professional digital solutions for artists and creators.</p>
  </div>

  <div class="cards">

    <div class="card">
      <div class="icon">🎤</div>
      <h3>Artist Verification</h3>
      <p>
        Build a professional identity and verification profile
        for your artistic career.
      </p>
    </div>

    <div class="card">
      <div class="icon">📱</div>
      <h3>Digital Promotion</h3>
      <p>
        Promote your work and strengthen your presence across
        digital platforms.
      </p>
    </div>

    <div class="card">
      <div class="icon">🌐</div>
      <h3>Online Presence</h3>
      <p>
        Create a professional digital profile that represents
        your talent and brand.
      </p>
    </div>

  </div>
</section>

<section class="verification" id="verification">
  <div class="verify-box">
    <div class="section-title">
      <h2>Artist Verification</h2>
      <p>
        Are you an artist, creator or digital talent?
        Start building your professional identity with us.
      </p>
    </div>

    <a class="btn primary"
       href="mailto:workanuragdigital@gmail.com?subject=Artist Verification Request">
       Apply for Verification
    </a>
  </div>
</section>

<section class="contact" id="contact">
  <div class="section-title">
    <h2>Contact Anurag Digital Media</h2>
    <p>For verification, promotion and digital media enquiries.</p>
  </div>

  <div class="contact-info">
    📞 <a href="tel:7464076840">7464076840</a>
    <br><br>
    📧 <a href="mailto:workanuragdigital@gmail.com">
      workanuragdigital@gmail.com
    </a>
  </div>
</section>

</main>

<footer>
  © 2026 Anurag Digital Media. All Rights Reserved.
</footer>

</body>
</html>
