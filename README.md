<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Different projects by English students</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(120deg, #e0c3fc 0%, #8ec5fc 100%);
      min-height: 100vh;
    }
    header {
      background: rgba(44, 62, 80, 0.95);
      color: #fff;
      padding: 30px 0 20px 0;
      text-align: center;
      box-shadow: 0 2px 8px rgba(44,62,80,0.1);
    }
    h1 {
      margin: 0;
      font-size: 2.8em;
      letter-spacing: 1px;
    }
    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background: rgba(255,255,255,0.9);
      border-radius: 16px;
      box-shadow: 0 4px 24px rgba(44,62,80,0.08);
    }
    .design-section {
      margin-bottom: 30px;
      padding: 18px 22px;
      border-left: 6px solid #8ec5fc;
      background: #f4f8fb;
      border-radius: 8px;
      transition: box-shadow 0.2s;
      box-shadow: 0 1px 6px rgba(44,62,80,0.07);
    }
    .design-section:hover {
      box-shadow: 0 4px 18px rgba(44,62,80,0.15);
      background: #e0f0ff;
    }
    .design-title {
      margin: 0 0 8px 0;
      color: #2d3e50;
      font-size: 1.3em;
      font-weight: bold;
    }
    .design-link {
      color: #3b82f6;
      text-decoration: none;
      font-size: 1.1em;
      transition: color 0.2s;
    }
    .design-link:hover {
      color: #2563eb;
      text-decoration: underline;
    }
    #qrcode {
      margin: 30px auto;
      width: 150px;
      height: 150px;
    }
    @media (max-width: 600px) {
      .container {
        margin: 10px;
        padding: 10px;
      }
      h1 {
        font-size: 2em;
      }
    }
  </style>
  <!-- Librería QRCode.js -->
  <script defer src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
  <script defer>
    document.addEventListener("DOMContentLoaded", function() {
      new QRCode(document.getElementById("qrcode"), {
        text: "https://zsebask.github.io/systems-proyects-gropu-B1/",
        width: 150,
        height: 150,
        colorDark: "#000000",
        colorLight: "#ffffff",
        correctLevel: QRCode.CorrectLevel.H
      });
    });
  </script>
</head>
<body>
  <header>
    <h1>Different projects by English students</h1>
  </header>
  <div class="container">
    <div class="design-section">
      <div class="design-title">Salud Mental</div>
      <a class="design-link" href="https://www.canva.com/design/DAGnENNxYO8/v6mkIt9B6fGs09-_iwG4AQ/edit?utm_content=DAGnENNxYO8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Mental health</a>
      <p></p>
    </div>
    <div class="design-section">
      <div class="design-title">Reciclaje para el planeta</div>
      <a class="design-link" href="https://www.canva.com/design/DAGpsAYPjzY/Z8OfEn4wRkXZ_Iaw7upeZA/edit?utm_content=DAGpsAYPjzY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Recycling</a>
      <p></p>
    </div>
    <div class="design-section">
      <div class="design-title">Ayuda de la Autoestima</div>
      <a class="design-link" href="https://www.canva.com/design/DAGpsFabqsk/e0x01yR5GV0Ah3XmoeAY0w/view?utm_content=DAGpsFabqsk&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h81603f5ec6" target="_blank">Self-esteem</a>
      <p></p>
    </div>
    <div class="design-section">
      <div class="design-title">Emprendimiento de galletas</div>
      <a class="design-link" href="https://www.canva.com/design/DAGpsFabqsk/e0x01yR5GV0Ah3XmoeAY0w/view?utm_content=DAGpsFabqsk&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h81603f5ec6ui=eyJEIjp7IlQiOnsiQSI6IlBCa0R5Q1pMa3dISENyMDcifX19&utm_content=DAGnRPxV7sc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Crumble chocoleit</a>
      <p></p>
    </div>
    <div class="design-section">
      <div class="design-title">Salud Mental en Chinchiná: Un Panorama General</div>
      <a class="design-link" href="https://gamma.app/docs/Salud-Mental-en-Chinchina-Un-Panorama-General-mwd7gzq5kom3di6" target="_blank">Mental and psychological movement</a>
      <p></p>
    </div>

    <!-- Código QR para la página -->
    <div id="qrcode"></div>
  </div>
</body>
</html>

