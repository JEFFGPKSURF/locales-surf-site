# locales-surf-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Locales Surf School Cancún</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Montserrat&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }
    header {
      background: linear-gradient(to right, #0099cc, #66cc99);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    h1, h2 {
      font-family: 'Archivo Black', sans-serif;
      margin: 0.5em 0;
    }
    .btn-whatsapp {
      position: fixed;
      bottom: 20px;
      left: 20px;
      background: #25D366;
      color: white;
      padding: 12px 18px;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      z-index: 9999;
    }
    .section {
      padding: 2rem;
      background: white;
      margin: 1rem;
      border-radius: 16px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .catalog {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1rem;
    }
    .package {
      background: #fff;
      border-radius: 12px;
      padding: 1rem;
      border: 1px solid #eee;
    }
    .price {
      color: #009688;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <a href="https://wa.me/5219981234567" class="btn-whatsapp">📲 Book via WhatsApp</a>

  <header>
    <h1>Locales Surf School Cancún</h1>
    <p>Learn to surf with locals. Sun, waves and pura vida 🇲🇽🏄‍♂️</p>
    <a href="#catalog" class="btn-whatsapp" style="left: auto; right: 20px; background: #ff5722;">View Catalog</a>
  </header>

  <section class="section" id="catalog">
    <h2>Surf Lessons & Packages</h2>
    <div class="catalog">
      <div class="package">
        <h3>🌊 Private Surf Lesson</h3>
        <p>Perfect for solo travelers or personalized coaching.</p>
        <p class="price">$1,100 MXN</p>
      </div>
      <div class="package">
        <h3>👨‍👩‍👧‍👦 Group Lesson</h3>
        <p>Fun for families, couples or friends. Great energy guaranteed!</p>
        <p class="price">$750 MXN per person</p>
      </div>
      <div class="package">
        <h3>🏄 Surf Camp 3 Días</h3>
        <p>Intensivo de 3 días con teoría + práctica + videoanálisis.</p>
        <p class="price">$2,900 MXN</p>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>¿Por qué elegirnos?</h2>
    <ul>
      <li>✔️ Instructores locales certificados</li>
      <li>✔️ Equipo incluido (tabla, lycra, leash)</li>
      <li>✔️ Experiencia auténtica 100% mexicana</li>
      <li>✔️ Clases en Playa Chac Mool</li>
    </ul>
  </section>

  <section class="section">
    <h2>Galería</h2>
    <p><em>Pronto añadiremos imágenes reales de nuestros alumnos surfeando en Cancún 📸</em></p>
  </section>

</body>
</html>

