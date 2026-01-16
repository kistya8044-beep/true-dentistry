# true-dentistry
index.html
<!DOCTYPE html><html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>True Dentistry — Стоматологія в Києві</title>
  <meta name="description" content="Сучасна стоматологія True Dentistry у Києві. Професійне лікування зубів, турбота та комфорт. Запис за телефоном +380978888528" />  <style>
    :root {
      --primary: #1fa4a9;
      --dark: #1c2b2e;
      --light: #f7fbfc;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: var(--light);
      color: var(--dark);
      line-height: 1.6;
    }

    header {
      background: white;
      padding: 20px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 0 20px;
    }

    .header-flex {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
      color: var(--primary);
    }

    .phone {
      color: var(--primary);
      font-weight: bold;
      text-decoration: none;
    }

    .hero {
      padding: 80px 20px;
      background: linear-gradient(135deg, #e6f6f7, #ffffff);
    }

    .hero h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 600px;
      margin-bottom: 30px;
      font-size: 18px;
    }

    .btn {
      display: inline-block;
      background: var(--primary);
      color: white;
      padding: 15px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 70px 20px;
    }

    .section-title {
      text-align: center;
      font-size: 30px;
      margin-bottom: 40px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 16px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.05);
      text-align: center;
    }

    .card h3 {
      margin-bottom: 10px;
      color: var(--primary);
    }

    .about {
      max-width: 800px;
      margin: auto;
      text-align: center;
      font-size: 18px;
    }

    .contacts {
      text-align: center;
      font-size: 18px;
    }

    footer {
      background: #0f1f22;
      color: white;
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 28px;
      }
    }
  </style></head>
<body><header>
  <div class="container header-flex">
    <!-- ЗАМІНІТЬ ЦЕЙ ТЕКСТ НА ЛОГОТИП (img), КОЛИ БУДЕ ПОТРІБНО -->
    <div class="logo">True Dentistry</div>
    <a class="phone" href="tel:+380978888528">+38 (097) 888-85-28</a>
  </div>
</header><section class="hero">
  <div class="container">
    <h1>Сучасна стоматологія в Києві</h1>
    <p>
      True Dentistry — це турбота, професіоналізм та комфорт.
      Ми допомагаємо зберегти здорову та красиву усмішку.
    </p>
    <a class="btn" href="tel:+380978888528">Записатися на прийом</a>
  </div>
</section><section>
  <div class="container">
    <h2 class="section-title">Наші послуги</h2>
    <div class="services">
      <div class="card">
        <h3>Терапевтичне лікування</h3>
        <p>Лікування карієсу та відновлення зубів</p>
      </div>
      <div class="card">
        <h3>Професійна гігієна</h3>
        <p>Чистка, полірування, профілактика</p>
      </div>
      <div class="card">
        <h3>Ортопедія</h3>
        <p>Коронки, вініри, протезування</p>
      </div>
      <div class="card">
        <h3>Імплантація</h3>
        <p>Сучасні та надійні рішення</p>
      </div>
    </div>
  </div>
</section><section style="background:#ffffff">
  <div class="container">
    <h2 class="section-title">Про клініку</h2>
    <p class="about">
      Ми працюємо з сучасним обладнанням та матеріалами.
      Для нас важливі безпека, комфорт і довіра кожного пацієнта.
    </p>
  </div>
</section><section>
  <div class="container">
    <h2 class="section-title">Наш лікар</h2>
    <div class="services" style="align-items:center">
      <div class="card">
        <img src="doctor.jpg" alt="Головний лікар Ковальова Ольга Анатоліївна" style="width:100%; max-width:260px; border-radius:16px; margin-bottom:15px" />
        <h3>Ковальова Ольга Анатоліївна</h3>
        <p><strong>Головний лікар<br>Ортодонт</strong></p>
        <p>Професійний підхід, індивідуальні плани лікування та турбота про кожного пацієнта.</p>
      </div>
    </div>
  </div>
</section><section>
  <div class="container">
    <h2 class="section-title">Контакти</h2>
    <div class="contacts">
      <p><strong>Адреса:</strong> м. Київ, вул. Князів Острозьких 41/8</p>
      <p><strong>Телефон:</strong> <a class="phone" href="tel:+380978888528">+38 (097) 888-85-28</a></p>
    </div>
  </div>
</section><footer>
  <p>© True Dentistry, Київ</p>
</footer></body>
</html>
