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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Locales Surf School Cancún</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Changa:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://unpkg.com/scrollreveal"></script>
  <style>
    body {
      background: #fdfaf6;
      font-family: 'Changa', sans-serif;
    }
    .service-item button {
      background: url('surfboard-icon.png') no-repeat center/contain;
      width: 120px;
      height: 40px;
      border: none;
      cursor: pointer;
      transition: transform 0.3s;
    }
    .service-item button:hover {
      transform: scale(1.1);
    }
    .wave-transition {
      animation: wave-slide 0.7s ease-in forwards;
    }
    @keyframes wave-slide {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px) rotate(-1deg); background-color: #e0f7fa; }
      100% { transform: translateY(0); background-color: #ffffff; }
    }
    .pricing-table {
      background: #fff8f2;
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.1);
      animation: slide-up 1s ease-out;
    }
    .pricing-table table {
      width: 100%;
      border-collapse: collapse;
    }
    .pricing-table th, .pricing-table td {
      border: 1px solid #ccc;
      padding: 12px 16px;
      text-align: left;
      font-size: 1rem;
    }
    .pricing-table thead {
      background: #ff9800;
      color: white;
    }
    .pricing-table tbody tr:hover {
      background: #fff0e0;
    }
    .pricing-table h3 {
      text-align: center;
      margin-bottom: 1rem;
      color: #e65100;
    }
    .secure-badge {
      display: inline-block;
      background: #dff0d8;
      color: #3c763d;
      border: 2px solid #3c763d;
      border-radius: 8px;
      padding: 0.5rem 1rem;
      margin-top: 1rem;
      font-weight: bold;
      font-size: 0.95rem;
      text-align: center;
      max-width: 300px;
      margin-left: auto;
      margin-right: auto;
    }
    .product-page {
      animation: wave-slide 0.7s ease-in-out;
      padding: 2rem;
      background: #f0faff;
      border-radius: 20px;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Locales Surf School Cancún</h1>
      <a class="whatsapp-btn" href="https://wa.me/5219981544063" target="_blank">📲 Book via WhatsApp</a>
    </div>
  </header>

  <section class="hero wave-transition">
    <h2 data-key="Learn to surf..." lang="en">Learn to surf with the real locals of Cancún</h2>
    <p>Authentic Mexican surf experience. Sun, waves, and pura vida. 🌊🇲🇽</p>
    <a class="cta-btn" href="https://wa.me/5219981544063" target="_blank">Book Your Class Now</a>
  </section>

  <section class="services">
    <h2>Surf Lessons & Packages</h2>
    <div class="service-list">
      <div class="service-item">
        <h3>Private Surf Lesson</h3>
        <p>90-minute class with all equipment included and a professional instructor. Perfect for solo travelers or personalized coaching.</p>
        <button onclick="showProduct('private')"></button>
      </div>
      <div class="service-item">
        <h3>Group Lessons</h3>
        <p>90-minute session with professional guidance and all gear provided. Fun for friends, families, or couples!</p>
        <button onclick="showProduct('group')"></button>
      </div>
      <div class="service-item">
        <h3>3-Class Package</h3>
        <p>Three 90-minute sessions including full equipment. Build skills progressively with professional coaching.</p>
        <button onclick="showProduct('package')"></button>
      </div>
      <div class="service-item">
        <h3>Photos & Video Package</h3>
        <p>Add-on: Drone and land photos/video of your 90-minute class to capture your best moments on the waves.</p>
        <button onclick="showProduct('media')"></button>
      </div>
    </div>

    <div class="pricing-table">
      <h3>🔥 Suggested Pricing Strategy</h3>
      <table>
        <thead>
          <tr>
            <th>Service</th>
            <th>Proposed Price</th>
            <th>Competitive Advantage</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Group Lesson (90 min)</td>
            <td>$65 USD / 1,300 MXN</td>
            <td>More affordable and attractive from the start</td>
          </tr>
          <tr>
            <td>Private Lesson (90 min)</td>
            <td>$90 USD / 1,800 MXN</td>
            <td>Best value for personalized coaching</td>
          </tr>
          <tr>
            <td>3-Class Package</td>
            <td>$180 USD / 3,600 MXN</td>
            <td>Averages $60/class – real savings</td>
          </tr>
          <tr>
            <td>Photos + Drone Video</td>
            <td>+ $50 USD</td>
            <td>Optional add-on for higher profit margin</td>
          </tr>
        </tbody>
      </table>
      <p>💬 Offer a guarantee or a discounted trial class to stand out!</p>
      <div class="secure-badge">🔒 Secure Booking · Trusted Local Business</div>
    </div>
  </section>

  <div id="product-detail" class="product-page" style="display: none">
    <h2 id="product-title">Title</h2>
    <p id="product-description">Description</p>
    <a class="cta-btn" href="https://wa.me/5219981544063" target="_blank">📩 Reserve this class now</a>
  </div>

  <script>
    const productData = {
      private: {
        title: 'Private Surf Lesson',
        description: '90-minute class with a professional local instructor and all equipment included. Ideal for solo travelers and fast progress.'
      },
      group: {
        title: 'Group Surf Lesson',
        description: '90-minute social surf session with full equipment and expert coaching. Fun and safe for all levels!'
      },
      package: {
        title: '3-Class Surf Package',
        description: 'Three 90-minute surf lessons with gear and pro instruction. Great value for consistent improvement.'
      },
      media: {
        title: 'Photo & Drone Video Package',
        description: 'Capture your surfing adventure with stunning drone and land footage. Add-on service for any class.'
      }
    };

    function showProduct(key) {
      const section = document.getElementById('product-detail');
      section.style.display = 'block';
      document.getElementById('product-title').textContent = productData[key].title;
      document.getElementById('product-description').textContent = productData[key].description;
      section.classList.add('wave-transition');
      window.scrollTo({ top: section.offsetTop, behavior: 'smooth' });
    }
  </script>
</body>
</html>



