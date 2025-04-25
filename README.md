# reyhannf.github.io-biodata
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Reyhan Nurfadilah - Portfolio</title>
  <link rel="icon" href="https://fav.farm/⚡" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #1e3c72, #2a5298);
      color: white;
      overflow-x: hidden;
      position: relative;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    .animated-circle {
      position: absolute;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.1);
      animation: float 6s ease-in-out infinite;
    }

    .circle1 { width: 150px; height: 150px; top: 5%; left: 10%; }
    .circle2 { width: 200px; height: 200px; bottom: 10%; right: 10%; }
    .circle3 { width: 100px; height: 100px; top: 50%; right: 30%; }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }

    .container {
      max-width: 800px;
      margin: auto;
      padding: 2rem 1rem;
      position: relative;
      z-index: 1;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 0;
      animation: fadeIn 1.5s ease;
    }

    h2 {
      font-weight: 400;
      margin-top: 0;
      color: #d0d0d0;
      animation: fadeIn 2s ease;
    }

    section {
      margin-top: 2rem;
    }

    h3 {
      color: #f5f5f5;
      margin-bottom: 0.5rem;
    }

    p, li {
      font-size: 1rem;
      line-height: 1.6;
      margin: 0.5rem 0;
    }

    ul {
      padding-left: 20px;
    }

    ul li::marker {
      color: #00ffff;
    }

    .button {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.8rem 1.5rem;
      background: #ffffff22;
      color: white;
      border: 1px solid white;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s;
    }

    .button:hover {
      background: #ffffff44;
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.8rem;
      color: #ccc;
      margin-top: auto;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="animated-circle circle1"></div>
  <div class="animated-circle circle2"></div>
  <div class="animated-circle circle3"></div>

  <div class="container">
    <h1>Reyhan Nurfadilah</h1>
    <h2>Fresh Graduate | IT Support Enthusiast</h2>

    <section>
      <h3>Tentang Saya</h3>
      <p>
        Saya lulusan SMK Tribakti Pangalengan jurusan TKJ (Teknologi Komputer dan Jaringan), dengan minat besar di bidang jaringan dan IT support. 
        Memiliki pengalaman PKL di Freenet selama 2 bulan dan sertifikasi MTCNA dari Mikrotik. 
        Siap belajar dan berkembang di dunia kerja profesional.
      </p>
    </section>

    <section>
      <h3>Pendidikan</h3>
      <p>SMK Tribakti Pangalengan, Jurusan TKJ<br/>Lulusan, 2025</p>
    </section>

    <section>
      <h3>Pengalaman</h3>
      <ul>
        <li>Membantu pemasangan dan pemeliharaan koneksi internet</li>
        <li>Mempelajari konfigurasi perangkat jaringan dasar</li>
        <li>Berinteraksi dengan pelanggan terkait kendala jaringan</li>
      </ul>
    </section>

    <section>
      <h3>Sertifikat & Prestasi</h3>
      <ul>
        <li>MTCNA (MikroTik Certified Network Associate), 2024</li>
        <li>Peserta lomba desain grafis tingkat sekolah</li>
        <li>Peserta lomba konfigurasi akses point jaringan</li>
      </ul>
    </section>

    <section>
      <h3>Kontak</h3>
      <ul>
        <li>Email: reyhannurfadilah7@gmail.com</li>
        <li>No/WA: 0857-2486-2084</li>
      </ul>
      <a href="mailto:reyhannurfadilah7@gmail.com" class="button">Hubungi Saya</a>
    </section>
  </div>

  <footer>
    © 2025 Reyhan Nurfadilah
  </footer>
</body>
</html>