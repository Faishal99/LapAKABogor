<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LapAKABogor Store</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    h1 {
      color: #264653;
    }
    .section-title {
      font-size: 1.5em;
      margin-top: 20px;
      color: #2a9d8f;
    }
    .list-item {
      margin: 10px 0;
    }
    .carousel img {
      width: 100%;
      height: auto;
    }
    .container {
      padding: 20px;
    }
    .feature-list {
      list-style-type: none;
      padding: 0;
    }
    .feature-list li {
      margin: 10px 0;
    }
    .feature-list li::before {
      content: "✔️";
      margin-right: 8px;
    }
    .contact-info {
      margin-top: 20px;
    }
    .contact-info a {
      color: #2a9d8f;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>LapAKABogor Store</h1>
    <p><strong>LapAKABogor</strong> adalah platform dagang satu halaman berbasis HTML yang ditujukan untuk menjual produk-produk UKM, IKM, dan inovasi mahasiswa Politeknik AKA Bogor. Website ini dibuat gratis menggunakan <strong>GitHub Pages</strong> dan mendukung fitur checkout langsung ke WhatsApp.</p>

    <h2 class="section-title">🔥 Fitur Utama</h2>
    <ul class="feature-list">
      <li>Carousel iklan produk utama (dapat digeser)</li>
      <li>Kategori produk:
        <ul>
          <li>Makanan Berat</li>
          <li>Makanan Ringan</li>
          <li>Minuman</li>
          <li>Alat dan Bahan Kimia</li>
          <li>Produk Inovasi Mahasiswa AKA</li>
          <li>Lain-lain</li>
        </ul>
      </li>
      <li>Formulir input pembeli:
        <ul>
          <li>Nama</li>
          <li>Prodi/Kelas</li>
          <li>Nomor WhatsApp</li>
          <li>Alamat pengiriman</li>
        </ul>
      </li>
      <li>Checkout WhatsApp otomatis:
        <ul>
          <li>Menampilkan semua item dan jumlah pesanan</li>
          <li>Total harga dihitung otomatis</li>
          <li>Biaya tambahan Rp1000/item jika memilih "diantar"</li>
          <li>Pilihan metode pembayaran: QRIS atau Cash</li>
        </ul>
      </li>
    </ul>

    <h2 class="section-title">🚀 Cara Menjalankan</h2>
    <ol>
      <li>Fork atau clone repositori ini.</li>
      <li>Buka GitHub dan aktifkan <strong>GitHub Pages</strong> melalui:
        <ul>
          <li><strong>Settings > Pages > Source > main branch</strong></li>
        </ul>
      </li>
      <li>Akses website kamu di: <strong>https://<username>.github.io/<repository>/</strong></li>
    </ol>

    <h2 class="section-title">👨‍💻 Teknologi</h2>
    <ul class="feature-list">
      <li>HTML5 + JavaScript murni (tanpa framework)</li>
      <li>Font Awesome untuk ikon</li>
      <li>GitHub Pages untuk hosting gratis</li>
    </ul>

    <h2 class="section-title">📸 Tampilan</h2>
    <p><img src="https://via.placeholder.com/728x300.png?text=Tampilan+LapAKABogor" alt="Tampilan Halaman"></p>

    <h2 class="section-title">📬 Kontak</h2>
    <p>Hubungi tim pengembang melalui email atau WhatsApp untuk kolaborasi lebih lanjut.</p>

    <div class="contact-info">
      <p>Email: <a href="mailto:developer@lapakabogor.com">developer@lapakabogor.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/6281234567890" target="_blank">+62 812 3456 7890</a></p>
    </div>

    <hr>

    <footer>
      <p>Website ini dikembangkan untuk mendukung kewirausahaan mahasiswa dan inovasi digital kampus Politeknik AKA Bogor.</p>
    </footer>
  </div>

</body>
</html>
