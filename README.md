<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ZyxraaBotzz | Website Resmi</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2e8e6b87b.js" crossorigin="anonymous">
</script>
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Rubik', sans-serif;
      background: linear-gradient(to bottom, #0f0f0f, #1c1c1c);
      color: #fff;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      animation: fadeIn 1s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header {
      background: radial-gradient(circle at center, #232323, #121212);
      text-align: center;
      border-bottom: 2px solid #00ffff;
      padding: 30px 0;
    }

    header img.logo {
      width: 120px;
      border-radius: 15px;
      transition: transform 0.4s ease;
    }

    header img.logo:hover {
      transform: scale(1.1) rotate(2deg);
    }

    header h1 {
      margin: 15px 0 5px;
      font-size: 2.8rem;
      color: #00ffff;
      text-shadow: 0 0 12px #00ffff88;
      letter-spacing: 2px;
    }

    header p {
      margin: 0;
      color: #ccc;
      font-style: italic;
      font-size: 1.1rem;
    }

    .banner {
      width: 100%;
      max-height: 350px;
      object-fit: cover;
      margin-top: 10px;
      box-shadow: 0 0 50px rgba(0, 255, 255, 0.15);
      border-radius: 0 0 20px 20px;
    }

    main {
      flex: 1;
      padding: 60px 20px 40px;
      max-width: 900px;
      margin: 0 auto;
      text-align: center;
    }

    main h2 {
      color: #00e1ff;
      font-size: 2.3rem;
      margin-bottom: 16px;
      text-transform: uppercase;
    }

    main p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: 0 auto 30px;
      line-height: 1.8;
      color: #ddd;
    }

    .button, .contact-button {
      background: linear-gradient(to right, #00ffff, #0099ff);
      color: white;
      padding: 14px 32px;
      border: none;
      border-radius: 10px;
      font-size: 1.15rem;
      cursor: pointer;
      transition: all 0.3s ease;
      margin: 10px;
      display: inline-block;
      text-decoration: none;
      box-shadow: 0 0 12px rgba(0, 255, 255, 0.3);
    }

    .button:hover, .contact-button:hover {
      transform: translateY(-2px);
      box-shadow: 0 0 18px #00ffff;
    }

    .button:active, .contact-button:active {
      transform: scale(0.95);
    }

    .button i, .contact-button i {
      margin-right: 8px;
    }

    .features {
      margin-top: 50px;
    }

    .features h3 {
      color: #0ff;
      font-size: 1.8rem;
      margin-bottom: 20px;
    }

    .features ul {
      list-style: none;
      padding: 0;
      color: #ccc;
      font-size: 1.1rem;
    }

    .features li {
      margin-bottom: 12px;
    }

    footer {
      text-align: center;
      padding: 20px 10px;
      background-color: #121212;
      font-size: 0.9rem;
      border-top: 1px solid #333;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.supa.codes/ft89YK" alt="Logo ZyxraaBotzz" class="logo" />
    <h1>ZyxraaBotzz</h1>
    <p>Smart. Fast. Trusted.</p>
  </header>

  <img src="https://i.supa.codes/ft89YK" alt="Banner ZyxraaBotzz" class="banner" />

  <main>
    <h2>Selamat datang!</h2>
    <p>ZyxraaBotzz adalah bot WhatsApp serbaguna yang dibuat untuk bantu kamu secara instan, 24/7. Dipakai lebih dari 10.000+ pengguna aktif!</p>

    <button class="button" onclick="window.open('https://chat.whatsapp.com/FYvRldvcz8f8fCuuaqWtlg', '_blank')">
      <i class="fas fa-rocket"></i>Coba Sekarang
    </button>

    <a href="https://wa.me/628817579553" target="_blank" class="contact-button" title="Hubungi Owner via WhatsApp">
      <i class="fab fa-whatsapp"></i>Contact Owner
    </a>

    <section class="features">
      <h3>Kenapa Pilih ZyxraaBotzz?</h3>
      <ul>
        <li>⚡ Cepat merespon perintah tanpa delay</li>
        <li>🛡️ Sistem anti-spam & auto-moderasi</li>
        <li>🤖 Banyak fitur unik: downloader, game, chatbot</li>
        <li>👨‍💼 Support owner langsung (fast response)</li>
      </ul>
    </section>

    <section class="payment">
      <h3 style="color:#00eaff; margin-top: 50px;">Dukung Kami</h3>
      <p style="color:#ccc; margin-bottom: 25px;">Kamu bisa memberikan donasi atau melakukan pembayaran melalui salah satu metode di bawah ini:</p>

      <img src="https://files.catbox.moe/9u6cvi.jpg"  style="cursor:pointer;" alt="QRIS ZyxraaBotzz" style="width:220px; border-radius:15px; box-shadow:0 0 15px #00eaff88; margin-bottom:20px;" />

      <div style="margin-top: 20px;">
        <button class="button" onclick="copyText('0881011106597')"><i class="fas fa-wallet"></i> Dana: 0881011106597</button>
        <button class="button" onclick="copyText('0881011106597')"><i class="fas fa-money-check-alt"></i> GoPay: 0881011106597</button>
      </div>
    </section>
  </main>
<!-- Modal QRIS -->
<div id="qrisModal" style="display:none; position:fixed; z-index:999; left:0; top:0; width:100%; height:100%; background-color:rgba(0,0,0,0.85); justify-content:center; align-items:center;">
  <span onclick="closeModal()" style="position:absolute; top:20px; right:30px; color:#fff; font-size:2rem; cursor:pointer;">&times;</span>
  <img src="https://files.catbox.moe/9u6cvi.jpg" style="max-width:90%; max-height:90%; border-radius:10px; box-shadow:0 0 25px #00eaff;" alt="QRIS Besar">
</div>


  <footer>
    &copy; 2025 ZyxraaBotzz. All rights reserved.
  </footer>

  <script>
    function copyText(text) {
      navigator.clipboard.writeText(text).then(() => {
        alert('Nomor berhasil disalin: ' + text);
      });
    }
  
</script>
</body>
</html>
