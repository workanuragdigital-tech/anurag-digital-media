<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anurag Digital Media</title>
  <meta name="description" content="Anurag Digital Media - Music Distribution, Artist Promotion and Verification">

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
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo {
      font-size: 22px;
      font-weight: 800;
    }

    .logo span {
      color: #ff3158;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
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
      background: radial-gradient(circle at top, #321322 0%, #0b0b0f 55%);
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
      max-width: 680px;
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
      transition: .2s;
    }

    .btn:hover {
      transform: translateY(-2px);
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

    /* MUSIC DISTRIBUTION */

    .music {
      background: #111116;
    }

    .music-intro {
      max-width: 760px;
      margin: 0 auto 40px;
      text-align: center;
      color: #bdbdc7;
    }

    .platforms {
      max-width: 1000px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .platform {
      background: #181820;
      border: 1px solid #30303b;
      border-radius: 15px;
      padding: 28px;
      text-align: center;
    }

    .platform-icon {
      font-size: 38px;
      margin-bottom: 12px;
    }

    .platform h3 {
      margin-bottom: 8px;
    }

    .platform p {
      color: #aaaab5;
      font-size: 14px;
    }

    .distribution-box {
      max-width: 1000px;
      margin: 40px auto 0;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .distribution-item {
      padding: 25px;
      border-radius: 14px;
      background: #15151c;
      border: 1px solid #292933;
    }

    .distribution-item h3 {
      margin-bottom: 8px;
    }

    .distribution-item p {
      color: #aaaab5;
      font-size: 14px;
    }

    .release-box {
      max-width: 800px;
      margin: 45px auto 0;
      padding: 40px 25px;
      text-align: center;
      background: #191922;
      border: 1px solid #ff3158;
      border-radius: 18px;
    }

    .release-box h3 {
      font-size: 28px;
      margin-bottom: 12px;
    }

    .release-box p {
      color: #bdbdc7;
      margin-bottom: 20px;
    }

    .verification {
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
        margin: 0 6px;
      }

      .cards,
      .platforms,
      .distribution-box {
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
  <div class="logo">
    Anurag <span>Digital Media</span>
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#music">Music</a>
    <a href="#verification">Verification</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

<!-- HERO -->

<section class="hero" id="home">
  <div class="hero-content">

    <div class="badge">
      DIGITAL MEDIA • MUSIC • ARTIST SERVICES
    </div>

    <h1>
      Your Talent.<br>
      <span>Your Digital Identity.</span>
    </h1>

    <p>
      Anurag Digital Media helps artists, singers, musicians and
      creators build their digital presence, distribute music and
      promote their work.
    </p>

    <div class="buttons">
      <a class="btn primary" href="#music">
        🎵 Distribute Your Music
      </a>

      <a class="btn secondary" href="#verification">
        Artist Verification
      </a>
    </div>

  </div>
</section>


<!-- SERVICES -->

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
        Build a professional artist identity and verification
        profile for your career.
      </p>
    </div>

    <div class="card">
      <div class="icon">📱</div>
      <h3>Artist Promotion</h3>
      <p>
        Promote your music, content and artist profile across
        digital platforms.
      </p>
    </div>

    <div class="card">
      <div class="icon">🌐</div>
      <h3>Digital Presence</h3>
      <p>
        Create a professional online identity that represents
        your talent and brand.
      </p>
    </div>

  </div>

</section>


<!-- MUSIC DISTRIBUTION -->

<section class="music" id="music">

  <div class="section-title">

    <div class="badge">
      MUSIC DISTRIBUTION
    </div>

    <h2>
      Take Your Music Worldwide
    </h2>

    <p>
      Release your songs and albums and build your audience
      across major digital music platforms.
    </p>

  </div>

  <div class="music-intro">
    Anurag Digital Media provides music distribution support
    for independent artists, singers, musicians and creators.
  </div>


  <!-- PLATFORMS -->

  <div class="platforms">

    <div class="platform">
      <div class="platform-icon">🎧</div>
      <h3>Spotify</h3>
      <p>
        Distribute your music and reach Spotify listeners.
      </p>
    </div>

    <div class="platform">
      <div class="platform-icon">▶️</div>
      <h3>YouTube Music</h3>
      <p>
        Get your music available for YouTube Music audiences.
      </p>
    </div>

    <div class="platform">
      <div class="platform-icon"></div>
      <h3>Apple Music</h3>
      <p>
        Make your releases available to Apple Music listeners.
      </p>
    </div>

  </div>


  <!-- DISTRIBUTION SERVICES -->

  <div class="distribution-box">

    <div class="distribution-item">
      <h3>🎵 Song Distribution</h3>
      <p>
        Submit your single and prepare it for digital music
        distribution.
      </p>
    </div>

    <div class="distribution-item">
      <h3>💿 Album Distribution</h3>
      <p>
        Release albums and multiple-track projects through
        digital distribution support.
      </p>
    </div>

    <div class="distribution-item">
      <h3>📈 Artist Promotion</h3>
      <p>
        Build awareness around your release and strengthen
        your artist presence.
      </p>
    </div>

  </div>


  <!-- RELEASE SUBMISSION -->

  <div class="release-box">

    <h3>
      Ready to Release Your Music?
    </h3>

    <p>
      Send us your release details and our team will contact
      you regarding the next steps.
    </p>

    <a
      class="btn primary"
      href="mailto:workanuragdigital@gmail.com?subject=Music Release Submission">
      🎵 Submit Your Release
    </a>

  </div>

</section>


<!-- VERIFICATION -->

<section id="verification">

  <div class="verify-box">

    <div class="section-title">

      <h2>Artist Verification</h2>

      <p>
        Are you an artist, singer, musician or digital creator?
        Start building your professional identity with us.
      </p>

    </div>

    <a
      class="btn primary"
      href="mailto:workanuragdigital@gmail.com?subject=Artist Verification Request">
      Apply for Verification
    </a>

  </div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

  <div class="section-title">

    <h2>
      Contact Anurag Digital Media
    </h2>

    <p>
      For music distribution, promotion, verification and
      digital media enquiries.
    </p>

  </div>

  <div class="contact-info">

    📞
    <a href="tel:7464076840">
      7464076840
    </a>

    <br><br>

    📧
    <a href="mailto:workanuragdigital@gmail.com">
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
