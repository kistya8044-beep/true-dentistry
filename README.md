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
