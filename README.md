<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Grafika Komputer - Syifa Nur Ramadhani</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #e5e5e5;
      color: #333;
    }

    header {
      background-color: #2e2e2e;
      color: #f0f0f0;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 15px 0;
    }

    nav a {
      color: #f0f0f0;
      text-decoration: none;
      font-weight: 600;
      padding: 10px 15px;
      border-radius: 6px;
      transition: background-color 0.3s;
    }

    nav a:hover {
      background-color: #666;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .profil {
      display: flex;
      flex-direction: column;
      align-items: center;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      margin-bottom: 40px;
    }

    .profil img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #888;
      margin-bottom: 20px;
    }

    .profil h2 {
      margin: 0;
      font-size: 1.6em;
      color: #222;
    }

    .profil p {
      text-align: center;
      max-width: 700px;
      margin-top: 10px;
      color: #555;
    }

    .section-title {
      font-size: 1.5em;
      margin-bottom: 20px;
      color: #222;
    }

    .tentang, .tugas {
      background-color: #f9f9f9;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      margin-bottom: 40px;
    }

    .tugas p {
      background-color: #ddd;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .tugas a {
      color: #2c2c2c;
      font-weight: bold;
      text-decoration: none;
    }

    .tugas a:hover {
      text-decoration: underline;
    }

    footer {
      background-color: #2e2e2e;
      color: #ccc;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Grafika Komputer</h1>
    <p>Syifa Nur Ramadhani - PTI</p>
  </header>

  <nav>
    <a href="#">Beranda</a>
    <a href="#profil">Profil</a>
    <a href="#tentang">Tentang</a>
    <a href="#tugas">Tugas</a>
  </nav>

  <div class="container">

    <section id="profil" class="profil">
      <img src="Foto/Syifa.jpg" alt="Foto profil">
      <h2>Syifa Nur Ramadhani</h2>
	  <h2>2413025019</h2>
      <p>Halo! Saya Syifa, mahasiswa PTI Universitas Negeri yang sedang mendalami mata kuliah Grafika Komputer. Saya tertarik pada dunia desain visual dan teknologi, terutama dalam pengembangan antarmuka grafis yang menarik dan fungsional.</p>
    </section>

    <section id="tentang" class="tentang">
      <h3 class="section-title">Tentang Halaman Ini</h3>
      <p>Website ini saya buat untuk mendokumentasikan seluruh tugas yang saya kerjakan selama mata kuliah Grafika Komputer. Di dalamnya terdapat tautan ke hasil tugas, kode program, serta video demonstrasi dari setiap praktik yang telah dilakukan.</p>
    </section>

    <section id="tugas" class="tugas">
      <h3 class="section-title">Daftar Tugas</h3>

      <p><strong>Tugas 1</strong><br>
        <a href="files/Tokoh.pdf">Hasil</a> |  
        <a href="https://drive.google.com/file/d/1soPdPBa1z7QB9YSMwwnTabk5bIzRCH7L/view?usp=drive_link">Video</a>
      </p>

      <p><strong>Tugas 2</strong><br>
        <a href="files/Garis.pdf">Hasil</a> |  
        <a href="https://drive.google.com/file/d/1x7bre_0bLeULsWzrROsYovoMSrDoukmq/view?usp=sharing">Video</a>
      </p>

      <p><strong>Tugas 3</strong><br>
        <a href="files/Lingkaran.pdf">Hasil</a> | 
        <a href="https://drive.google.com/file/d/197DhXJC35zZmnLEX766WZGcuJ0jb4nkw/view?usp=drive_link">Video</a>
      </p>
    </section>

  </div>

  <footer>
    <p>Hak Cipta &copy; 2025 Syifa Nur Ramadhani</p>
  </footer>

</body>
</html>
