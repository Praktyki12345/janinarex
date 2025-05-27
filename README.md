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
    }
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 30px;
      background-color: #f3edf7;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }
    header img {
      height: 90px;
    }
    nav a {
      margin-left: 25px;
      text-decoration: none;
      color: #704d99;
      font-weight: bold;
    }
    .hero {
      margin-top: 110px;
      background: url('IMG_0054-2.jpg') center/cover no-repeat;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      filter: brightness(0.7);
    }
    .hero-text {
      position: absolute;
      color: white;
      font-size: 2.5rem;
      font-weight: bold;
    }
    .section {
      padding: 60px 30px;
      max-width: 1100px;
      margin: auto;
    }
    .o-salonie {
      display: flex;
      gap: 40px;
      align-items: center;
    }
    .o-salonie img {
      max-width: 400px;
      border-radius: 10px;
    }
    .uslugi {
      text-align: center;
    }
    .uslugi-images {
      display: flex;
      justify-content: space-around;
      margin-top: 30px;
      gap: 20px;
    }
    .uslugi-images div {
      flex: 1;
    }
    .uslugi-images img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 10px;
    }
    .uslugi-images p {
      margin-top: 10px;
      font-weight: bold;
    }
    .kosmetyki-item {
      display: flex;
      align-items: flex-start;
      gap: 30px;
      margin-bottom: 40px;
    }
    .kosmetyki-item img {
      width: 300px;
      border-radius: 10px;
    }
    .kontakt {
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .kontakt iframe {
      width: 100%;
      max-width: 700px;
      height: 450px;
      border: 0;
      border-radius: 10px;
    }
    .kontakt-info {
      margin-top: 20px;
      max-width: 300px;
    }
    footer {
      background-color: #eae3f0;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #333;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo" />
    <nav>
      <a href="#glowna">Główna</a>
      <a href="#o-salonie">O Salonie</a>
      <a href="#uslugi">Usługi</a>
      <a href="#kosmetyki">Kosmetyki</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </header>

  <section class="hero" id="glowna">
    <div class="hero-text">Salon Fryzjerski Janina Rex</div>
  </section>

  <section class="section o-salonie" id="o-salonie">
    <img src="IMG_0087.jpg" alt="Salon" />
    <div>
      <h2>O Salonie</h2>
      <p>Salon Fryzjerski Janina Rex oferuje stylizację zarówno dla kobiet, jak i mężczyzn. Nasza oferta obejmuje klasyczne cięcia, nowoczesne metamorfozy, koloryzacje oraz stylizacje okolicznościowe. Dzięki naszemu doświadczeniu i pasji gwarantujemy pełne zadowolenie z każdej wizyty.</p>
    </div>
  </section>

  <section class="section uslugi" id="uslugi">
    <h2>Usługi</h2>
    <div class="uslugi-images">
      <div>
        <img src="d3bda204-7a8b-4372-9352-10ef2e472237.jpg" alt="Koloryzacja" />
        <p>Koloryzacja</p>
      </div>
      <div>
        <img src="fryzjerka-strzyzenie-klienta.jpg" alt="Strzyżenie męskie" />
        <p>Strzyżenie męskie</p>
      </div>
      <div>
        <img src="IMG_0287.jpg" alt="Strzyżenie damskie" />
        <p>Strzyżenie damskie</p>
      </div>
    </div>
  </section>

  <section class="section" id="kosmetyki">
    <h2 style="text-align:center;">Kosmetyki</h2>
    <div class="kosmetyki-item">
      <div>
        <h3>Koloryzacje z Beauty Fusion</h3>
        <p>Beauty Fusion Naturalna koloryzacja najwyższej jakości, bez PPD oraz rezorcyny! Beauty Fusion to idealny wybór dla:
        <ul>
          <li>osób o delikatnej lub wrażliwej skórze głowy,</li>
          <li>kobiet w ciąży i mam karmiących (po konsultacji z lekarzem),</li>
          <li>klientów ceniących naturalność i jakość premium.</li>
        </ul>
        🌸 Efekt? Zdrowe, lśniące włosy i głęboki, równomierny kolor – bez kompromisów!</p>
      </div>
      <img src="IMG_0242.jpg" alt="Beauty Fusion" />
    </div>
    <div class="kosmetyki-item">
      <div>
        <h3>Kolory Beauty Fusion</h3>
        <p>Paleta kolorów Beauty Fusion stworzona została z myślą o wyjątkowej pielęgnacji i indywidualnych potrzebach klienta.</p>
      </div>
      <img src="IMG_0250.jpg" alt="Kolory Beauty Fusion" />
    </div>
    <div class="kosmetyki-item">
      <div>
        <h3>Artègo</h3>
        <p>🎨 Artego – Profesjonalna koloryzacja, która pielęgnuje. Artego to renomowana włoska marka, znana z wysokiej jakości produktów fryzjerskich. Ich system koloryzacji to coś więcej niż zwykła farba – to pielęgnacja i styl w jednym. Dzięki innowacyjnym formułom, farby Artego zapewniają intensywny kolor, maksymalną trwałość i jednocześnie ochronę włosa podczas zabiegu.</p>
      </div>
      <img src="IMG_0253.jpg" alt="Artego" />
    </div>
  </section>

  <section class="section kontakt" id="kontakt">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2442.235052170656!2d20.43732537664464!3d52.051682671926576!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47193360246d83fb%3A0x509bf0032954e70c!2sJ%C3%B3zefa%20Mireckiego%2041%2F43%2C%2096-300%20%C5%BByrard%C3%B3w!5e0!3m2!1spl!2spl!4v1716211262145!5m2!1spl!2spl" allowfullscreen></iframe>
    <div class="kontakt-info">
      <h3>Kontakt</h3>
      <p><strong>Telefon:</strong> +48 508 220 640</p>
      <p><strong>Godziny otwarcia:</strong><br>Pon–Pt: 09:00–18:00<br>Sobota: 08:00–16:00</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Salon Fryzjerski Janina Rex. Wszelkie prawa zastrzeżone.
  </footer>
</body>
</html>
