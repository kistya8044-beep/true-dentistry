<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>True Dentistry — Преміальна стоматологія в Києві</title>

  <meta name="description" content="True Dentistry — преміальна стоматологія в Києві. Сучасне лікування, професійні лікарі, комфорт та турбота.">

  <style>
    :root {
      --gold: #E2C28F;
      --dark: #0A0F1A;
      --deep-dark: #050910;
      --text-light: #d6d6d6;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: var(--dark);
      color: #ffffff;
      line-height: 1.6;
    }

    /* ================= HEADER ================= */
    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: var(--dark);
      border-bottom: 1px solid rgba(255,255,255,0.08);
    }

    .header-container {
      max-width: 1200px;
      margin: auto;
      padding: 16px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo img {
      height: 46px;
      width: auto;
    }

    nav a {
      color: #ffffff;
      text-decoration: none;
      margin: 0 16px;
      font-size: 16px;
      transition: 0.3s;
    }

    nav a:hover {
      color: var(--gold);
    }

    .call-btn {
      background: var(--gold);
      color: var(--dark);
      padding: 12px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
      white-space: nowrap;
    }

    .call-btn:hover {
      background: #c9a86c;
    }

    /* ================= HERO ================= */
    .hero {
      padding: 120px 20px;
      text-align: center;
      background: linear-gradient(180deg, var(--dark), var(--deep-dark));
    }

    .hero h1 {
      font-size: 42px;
      color: var(--gold);
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 700px;
      margin: 0 auto 30px;
      font-size: 20px;
      color: var(--text-light);
    }

    .hero .btn {
      display: inline-block;
      background: var(--gold);
      color: var(--dark);
      padding: 15px 32px;
      border-radius: 30px;
      font-size: 18px;
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
    }

    .hero .btn:hover {
      background: #c9a86c;
    }

    /* ================= SECTIONS ================= */
    section {
      max-width: 1200px;
      margin: auto;
      padding: 90px 20px;
    }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 50px;
      color: var(--gold);
    }

    /* ================= SERVICES ================= */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
    }

    .card {
      background: var(--deep-dark);
      padding: 30px;
      border-radius: 16px;
      text-align: center;
      border: 1px solid rgba(255,255,255,0.06);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: var(--gold);
    }

    .card h3 {
      color: var(--gold);
      margin-bottom: 12px;
      font-size: 20px;
    }

    .card p {
      color: var(--text-light);
    }

    /* ================= ABOUT ================= */
    .about-text {
      max-width: 800px;
      margin: auto;
      text-align: center;
      font-size: 19px;
      color: var(--text-light);
    }

    /* ================= DOCTOR ================= */
    .doctor {
      text-align: center;
    }

    .doctor-photo {
      width: 100%;
      max-width: 260px;
      border-radius: 20px;
      margin-bottom: 20px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.4);
    }

    .doctor h3 {
      font-size: 22px;
      color: var(--gold);
      margin-bottom: 6px;
    }

    .doctor p {
      color: var(--text-light);
      max-width: 600px;
      margin: 10px auto 0;
    }

    /* ================= CONTACTS ================= */
    .contacts {
      text-align: center;
    }

    .contacts p {
      font-size: 18px;
      margin-bottom: 10px;
    }

    .contacts a {
      color: var(--gold);
      text-decoration: none;
      font-weight: bold;
    }

    iframe {
      margin-top: 30px;
      width: 100%;
      height: 380px;
      border: 0;
      border-radius: 16px;
    }

    /* ================= FOOTER ================= */
    footer {
      background: var(--deep-dark);
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
      color: #aaa;
    }

    /* ================= MOBILE ================= */
    @media (max-width: 768px) {
      nav {
        display: none;
      }

      .hero h1 {
        font-size: 30px;
      }

      .hero p {
        font-size: 16px;
      }
    }
  </style>
</head>

<body>

<!-- HEADER -->
<header>
  <div class="header-container">
    <div class="logo">
      <img src="logo.png" alt="True Dentistry">
    </div>

    <nav>
      <a href="#services">Послуги</a>
      <a href="#about">Про нас</a>
      <a href="#doctor">Лікар</a>
      <a href="#contacts">Контакти</a>
    </nav>

    <a class="call-btn" href="tel:+380978888528">📞 Зателефонувати</a>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <h1>Преміальна стоматологія в Києві</h1>
  <p>
    Сучасні технології, професійні лікарі та максимальний комфорт.
    True Dentistry — турбота про вашу усмішку.
  </p>
  <a href="tel:+380978888528" class="btn">Записатися на прийом</a>
</section>

<!-- SERVICES -->
<section id="services">
  <h2 class="section-title">Наші послуги</h2>

  <div class="services">
    <div class="card">
      <h3>Терапевтичне лікування</h3>
      <p>Лікування карієсу та відновлення зубів</p>
    </div>

    <div class="card">
      <h3>Професійна гігієна</h3>
      <p>Чистка AirFlow, полірування, профілактика</p>
    </div>

    <div class="card">
      <h3>Ортопедія</h3>
      <p>Коронки, вініри, протезування</p>
    </div>

    <div class="card">
      <h3>Імплантація</h3>
      <p>Сучасні та надійні імпланти</p>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <h2 class="section-title">Про клініку</h2>
  <p class="about-text">
    Ми використовуємо сучасне обладнання та новітні методи лікування.
    Для нас важливі безпека, комфорт та довіра кожного пацієнта.
  </p>
</section>

<!-- DOCTOR -->
<section id="doctor">
  <h2 class="section-title">Головний лікар</h2>

  <div class="doctor">
    <img src="doctor.jpg" alt="Ковальова Ольга Анатоліївна" class="doctor-photo">
    <h3>Ковальова Ольга Анатоліївна</h3>
    <strong>Ортодонт, головний лікар</strong>
    <p>
      Індивідуальний підхід до кожного пацієнта, сучасні методи лікування
      та увага до деталей.
    </p>
  </div>
</section>

<!-- CONTACTS -->
<section id="contacts">
  <h2 class="section-title">Контакти</h2>

  <div class="contacts">
    <p><strong>Адреса:</strong> м. Київ, вул. Князів Острозьких 41/8</p>
    <p><strong>Телефон:</strong> <a href="tel:+380978888528">+38 (097) 888-85-28</a></p>

    <iframe
      src="https://www.google.com/maps?q=Князів+Острозьких+41/8+Київ&output=embed"
      loading="lazy">
    </iframe>
  </div>
</section>

<footer>
  © True Dentistry, Київ. Усі права захищено.
</footer>

</body>
</html>
