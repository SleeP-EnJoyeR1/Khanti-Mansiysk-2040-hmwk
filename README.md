# Khanti-Mansiysk-2040-hmwk
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ханты‑Мансийск 2040: искусство Севера</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Georgia', serif;
    }

    body {
      color: #333;
      line-height: 1.6;
    }

    /* Главный экран */
    .hero {
      background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://placehold.co/1920x1080') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 120px 20px;
      position: relative;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 700px;
      margin: 0 auto 30px;
      font-size: 1.2rem;
    }

    .cta-button {
      display: inline-block;
      background-color: #4CAF50;
      color: white;
      padding: 12px 24px;
      border-radius: 4px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s;
    }

    .cta-button:hover {
      background-color: #45a049;
    }

    /* Общие стили */
    section {
      padding: 60px 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2.2rem;
    }

    /* Манифест */
    .manifesto {
      background-color: #f9f9f9;
    }

    .manifesto p {
      max-width: 800px;
      margin: 20px auto;
      text-align: justify;
    }

    .manifesto ul {
      max-width: 600px;
      margin: 30px auto;
      list-style-position: inside;
    }

    /* Гид по локациям */
    .locations {
      background-color: #eef7ef;
    }

    .location-card {
      background-color: white;
      border-radius: 8px;
      padding: 20px;
      margin: 15px auto;
      max-width: 600px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    /* Новости */
    .news {
      background-color: #f5f5f5;
    }

    .news-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 0 20px;
    }

    .news-card {
      background-color: white;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    /* Команда */
    .team {
      background-color: #f0f7f0;
    }

    .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 0 20px;
    }

    .team-card {
      text-align: center;
      padding: 20px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .team-card img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
    }

    /* Проблемы */
    .issues {
      background-color: #222;
      color: white;
    }

    .issues ul {
      max-width: 700px;
      margin: 30px auto;
      list-style-position: inside;
    }

    /* Связь */
    .contact {
      background-color: #f0f7f0;
      text-align: center;
    }

    .contact-form {
      max-width: 500px;
      margin: 30px auto;
      padding: 20px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .form-group {
      margin-bottom: 15px;
      text-align: left;
    }

    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    input, select, textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }

    button {
      background-color: #4CAF50;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-weight: bold;
    }

    button:hover {
      background-color: #45a049;
    }


.social-links {
      margin-top: 20px;
    }

    .social-links a {
      color: #4CAF50;
      margin: 0 10px;
      text-decoration: none;
    }

    /* Футер */
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 30px 20px;
      position: relative;
    }

    footer::before {
      content: '';
      position: absolute;
      top: 0;
      left: 50%;
      width: 80%;
      height: 1px;
      background-color: #4CAF50;
      transform: translateX(-50%);
    }

    footer img {
      width: 40px;
      vertical-align: middle;
      margin-right: 10px;
    }

    .footer-nav {
      margin: 20px 0;
    }

    .footer-nav a {
      color: #aaa;
      margin: 0 10px;
      text-decoration: none;
    }

    .footer-nav a:hover {
      color: white;
    }
  </style>
</head>
<body>

<!-- 1. Главный экран -->
<section class="hero">
  <h1>Ханты‑Мансийск 2040: где мамонты говорят с нейросетями</h1>
  <p>Добро пожаловать в город‑музей под открытым небом. Здесь цифровое и традиционное сплетаются в «северный модерн»:</p>
  <ul>
    <li>голограммы оживляют древние орнаменты;</li>
    <li>кинетические скульптуры танцуют с бронзовыми мамонтами;</li>
    <li>нейросети пишут картины по вашим рассказам.</li>
  </ul>
