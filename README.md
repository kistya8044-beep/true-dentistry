<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>True Dentistry — Преміальна стоматологія в Києві</title>

  <style>
    body {
      margin: 0;
      font-family: "Arial", sans-serif;
      background: #0A0F1A;
      color: #ffffff;
      line-height: 1.6;
    }

    :root {
      --gold: #E2C28F;
      --dark: #0A0F1A;
      --deep-dark: #050910;
    }

    /* HEADER */
    .header {
      width: 100%;
      padding: 20px 40px;
      background: var(--dark);
      border-bottom: 1px solid rgba(255,255,255,0.08);
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo img {
      height: 42px;
      display: block;
      object-fit: contain;
    }

    .nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 18px;
      font-size: 16px;
      transition: 0.3s;
    }

    .nav a:hover {
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
    }

    .call-btn:hover {
      background: #c9a86c;
    }

    /* HERO */
    .hero {
      padding: 120px 20px;
      text-align: center;
      background: linear-gradient(180deg, #0A0F1A 0%, #050910 100%);
    }

    .hero h1 {
      font-size: 42px;
      color: var(--gold);
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 20px;
      max-width: 700px;
      margin: 0 auto 30px;
      color: #d6d6d6;
    }

    .btn {
      display: inline-block;
      background: var(--gold);
      color: var(--dark);
      padding: 15px 30px;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
      font-size: 18px;
      transition: 0.3s;
    }

    .btn:hover {
      background: #c9a86c;
    }

    /* SECTIONS */
    section {
      padding: 80px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 50px;
      color: var(--gold);
      letter-spacing: 1px;
    }

    /* SERVICES */
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
      border: 1px solid rgba(255,255,255,0.05);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: var(--gold);
    }

    .card h3 {
      color: var(--gold);
      margin-bottom: 10px;
      font-size: 20px;
    }

    /* DOCTOR */
    .doctor-photo {
      width: 100%;
      max-width: 270px;
      border-radius: 16px;
      margin-bottom: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.4);
    }

    /* CONTACTS */
    .contacts p {
      font-size: 18px;
    }

    .contacts a {
      color: var(--gold);
      font-weight: bold;
      text-decoration: none;
    }

    /* FOOTER */
    footer {
      background: #050910;
      padding: 30px 20px;
      text-align: center;
      color: #aaa;
      font-size: 14px;
    }

    /* MOBILE */
    @media (max-width: 768px) {
      .nav { display: none; }
      .header { padding: 14px 20px; }
      .hero h1 { font-size: 30px; }
      .hero p { font-size: 16px; }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header class="header">
    <div class="logo">
      <img src="logo.png" alt="True Dentistry Logo">
    </div>

    <nav class="nav">
      <a href="#services">Послуги</a>
      <a href="#about">Про нас</a>
      <a href="#doctor">Лікар</a>
      <a href="#contacts">Контакти</a>
    </nav>

    <a class="call-btn" href="tel:+380978888528">📞 Зателефонувати</a>
  </header>

  <!-- HERO -->
  <section class="hero">
    <h1>Преміальна стоматологія в Києві</h1>
    <p>Сучасне обладнання, професійні лікарі та комфортне лікування.  
      True Dentistry — турбота про вашу усмішку.</p>

    <a class="btn" href="tel:+380978888528">Записатися на прийом</a>
  </section>

  <!-- SERVICES -->
  <section id="services">
    <h2 class="section-title">Наші послуги</h2>

    <div class="services">
      <div class="card">
        <h3>Терапевтичне лікування</h3>
        <p>Лікування карієсу, пломбування та відновлення зубів.</p>
      </div>

      <div class="card">
        <h3>Професійна гігієна</h3>
        <p>AirFlow, полірування, профілактика.</p>
      </div>

      <div class="card">
        <h3>Ортопедія</h3>
        <p>Вініри, коронки, протезування преміального рівня.</p>
      </div>

      <div class="card">
        <h3>Імплантація</h3>
        <p>Сучасні матеріали та технології.</p>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2 class="section-title">Про клініку</h2>
    <p style="font-size:19px; text-align:center; color:#d6d6d6; max-width:800px; margin:auto;">
      Ми працюємо з використанням сучасного обладнання та новітніх технологій.
      Для нас важливі комфорт, безпека та довіра кожного пацієнта.
    </p>
  </section>

  <!-- DOCTOR -->
  <section id="doctor">
    <h2 class="section-title">Головний лікар</h2>

    <div style="text-align:center;">
      <img class="doctor-photo" src="doctor.jpg" alt="Ковальова Ольга Анатоліївна">
      
      <h3 style="color:var(--gold); font-size:22px;">Ковальова Ольга Анатоліївна</h3>
      <p><strong>Ортодонт, головний лікар</strong></p>

      <p style="max-width:600px; margin:auto; color:#d6d6d6;">
        Індивідуальний підхід до кожного пацієнта, сучасні методи лікування та увага до деталей.
      </p>
    </div>
  </section>

  <!-- CONTACTS -->
  <section id="contacts">
    <h2 class="section-title">Контакти</h2>

    <div class="contacts" style="text-align:center;">
      <p><strong>Адреса:</strong> м. Київ, вул. Князів Острозьких 41/8</p>
      <p><strong>Телефон:</strong> <a href="tel:+380978888528">+38 (097) 888-85-28</a></p>

      <br>

      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2539.427372054186!2d30.543843!3d50.4264066"
        width="100%" height="380" style="border:0; border-radius:16px;" allowfullscreen loading="lazy">
      </iframe>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © True Dentistry, Київ. Усі права захищено.
  </footer>

</body>
</html>
