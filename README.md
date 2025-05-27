<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Salon Fryzjerski Janina Rex</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      color: #333;
      line-height: 1.6;
    }

    header {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      padding: 10px 20px;
      background-color: #f3edf7;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }

    header img {
      height: 70px;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-end;
      gap: 15px;
      margin-top: 10px;
    }

    nav a {
      text-decoration: none;
      color: #704d99;
      font-weight: bold;
      font-size: 0.95rem;
    }

    .hero {
      margin-top: 100px;
      background: url('IMG_0054-2.jpg') center/cover no-repeat;
      height: 300px;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      filter: brightness(0.7);
    }

    .hero-text {
      position: absolute;
      color: white;
      font-size: 2rem;
      font-weight: bold;
      text-align: center;
      padding: 0 20px;
    }

    .section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .o-salonie {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      align-items: center;
    }

    .o-salonie img {
      max-width: 100%;
      border-radius: 10px;
      flex: 1 1 300px;
    }

    .o-salonie div {
      flex: 1 1 300px;
    }

    .uslugi {
      text-align: center;
    }

    .uslugi-images {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 30px;
      gap: 20px;
    }

    .uslugi-images div {
      flex: 1 1 280px;
    }

    .uslugi-images img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 10px;
    }

    .uslugi-images p {
      margin-top: 10px;
      font-weight: bold;
    }

    .kosmetyki-item {
      display: flex;
      flex-wrap: wrap;
      align-items: flex-start;
      gap: 20px;
      margin-bottom: 40px;
    }

    .kosmetyki-item img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
    }

    .kosmetyki-item div {
      flex: 1 1 300px;
    }

    .kontakt {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
    }

    .kontakt iframe {
      width: 100%;
      max-width: 100%;
      height: 350px;
      border: 0;
      border-radius: 10px;
    }

    .kontakt-info {
      flex: 1 1 300px;
    }

    footer {
      background-color: #eae3f0;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #333;
    }

    @media (max-width: 600px) {
      .hero {
        height: 220px;
      }

      .hero-text {
        font-size: 1.5rem;
      }

      nav {
        flex-direction: column;
        align-items: flex-start;
        margin-top: 5px;
      }

      header {
        flex-direction: column;
        align-items: flex-start;
      }

      .uslugi-images img {
        height: 180px;
      }

      .kontakt-info {
        max-width: 100%;
      }

      .uslugi-images div {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>
  <!-- pozostała część HTML bez zmian -->
