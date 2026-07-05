<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resmi Paskagrinda - Pasukan Pengibar Bendera</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            background-color: #f8f9fa;
            color: #2c3e50;
            line-height: 1.7;
        }

        /* === BAGIAN HEADER (BISA DIUBAH WARNA) === */
        header {
            background: linear-gradient(135deg, #b71c1c, #d32f2f);
            color: white;
            padding: 2.5rem 1rem;
            text-align: center;
        }

        header h1 {
            font-size: 2rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.1rem;
            opacity: 0.95;
        }

        /* === BAGIAN NAVIGASI === */
        nav {
            background: #212121;
            padding: 0.8rem;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: 500;
        }

        nav a:hover {
            color: #ffd700;
        }

        /* === BAGIAN ISI KONTEN === */
        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .section {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        .section h2 {
            color: #b71c1c;
            margin-bottom: 1.2rem;
            border-bottom: 2px solid #ffd700;
            padding-bottom: 0.5rem;
        }

        /* === BAGIAN GAMBAR (MUDAH DIUBAH) === */
        .foto-paskibra {
            width: 100%;
            max-height: 450px;
            object-fit: cover;
            border-radius: 10px;
            margin: 1.2rem 0;
            border: 3px solid #ffd700;
        }

        .foto-kecil {
            max-width: 350px;
            display: block;
            margin: 1rem auto;
            border-radius: 8px;
            border: 2px solid #ddd;
        }

        /* === BAGIAN FOOTER === */
        footer {
            background: #212121;
            color: white;
            text-align: center;
            padding: 1.5rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

<!-- ==============================================
   BAGIAN INI SEMUA BISA KAMU EDIT SESUKA HATI
   ============================================== -->

<header>
    <h1>PASKAGRINDA</h1>
    <p>Pasukan Pengibar Bendera Merah Putih - Resmi & Terpercaya</p>
</header>

<nav>
    <a href="#sejarah">Sejarah</a>
    <a href="#tentang">Tentang Kami</a>
    <a href="#galeri">Galeri Foto</a>
    <a href="#kontak">Kontak</a>
</nav>

<div class="container">

    <!-- === BAGIAN SEJARAH TERCIPTANYA PASKIBRA === -->
    <section class="section" id="sejarah">
        <h2>Sejarah Lahirnya Paskibra</h2>

        <!-- GANTI FOTO UTAMA: UBAH ALAMAT DI DALAM src="" -->
        <img src="https://images.unsplash.com/photo-1551836022-d5d88e9218df?ixlib=rb-4.0.3&auto=format&fit=crop&w=900&q=80" 
             alt="Upacara Pengibaran Bendera" class="foto-paskibra">

        <p>Paskibra atau Pasukan Pengibar Bendera Pusaka pertama kali dibentuk pada tahun 1946 atas inisiatif <b>Letnan Kolonel Husein Mutahar</b>. Tujuannya adalah untuk mengibarkan Bendera Merah Putih pada peringatan kemerdekaan Republik Indonesia yang pertama di Istana Merdeka Jakarta.</p>
        <br>
        <p>Awalnya pasukan ini beranggotakan 17 orang pengawal, 8 orang pembawa bendera, dan 45 orang pengawal kehormatan — angka ini melambangkan tanggal kemerdekaan <b>17 Agustus 1945</b>. Seiring berjalannya waktu, Paskibra menjadi simbol persatuan, kedisiplinan, dan semangat nasionalisme generasi muda Indonesia.</p>
        <br>
        <p>Sejak saat itu, setiap tahun pada tanggal 17 Agustus, Paskibra selalu menjadi bagian paling penting dalam upacara peringatan kemerdekaan di seluruh Indonesia, hingga terbentuklah Paskagrinda sebagai perwujudan semangat tersebut di daerah kami.</p>
    </section>

    <!-- === BAGIAN TENTANG PASKAGRINDA === -->
    <section class="section" id="tentang">
        <h2>Tentang Paskagrinda</h2>
        <p><b>Paskagrinda</b> adalah pasukan pengibar bendera yang dibentuk dengan tujuan menanamkan rasa cinta tanah air, kedisiplinan, dan tanggung jawab kepada generasi muda. Kami berkomitmen untuk menjaga tradisi dan menghormati jasa para pahlawan bangsa.</p>
        <p>Di sini kami berlatih bersama, membangun persaudaraan, dan melatih kemampuan diri untuk bisa tampil terbaik saat mengemban tugas mulia mengibarkan bendera kebanggaan bangsa.</p>
    </section>

    <!-- === BAGIAN GALERI FOTO (BISA DITAMBAH & DIUBAH) === -->
    <section class="section" id="galeri">
        <h2>Galeri Foto Paskagrinda</h2>
        <p>Berikut adalah dokumentasi kegiatan dan latihan kami:</p>

        <!-- CARA MENAMBAH FOTO: Salin baris di bawah lalu ubah alamat gambarnya -->
        <img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" 
             alt="Latihan Baris Berbaris" class="foto-kecil">

        <img src="https://images.unsplash.com/photo-1580477667995-2b94f01c9516?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" 
             alt="Bersama Anggota Paskibra" class="foto-kecil">
    </section>

    <!-- === BAGIAN KONTAK / INFORMASI LAIN === -->
    <section class="section" id="kontak">
        <h2>Informasi & Kontak</h2>
        <p>Jika ingin mengetahui lebih lanjut tentang Paskagrinda, silakan hubungi kami melalui:</p>
        <p>📍 Alamat: Banjarmasin, Kalimantan Selatan</p>
        <p>📞 Telepon: (Bisa diisi nomor kamu nanti)</p>
        <p>📧 Email: (Bisa diisi alamat email kamu nanti)</p>
    </section>

</div>

<footer>
    <p>&copy; 2026 Paskagrinda | Situs Resmi - Semua Bisa Diedit Sesuai Kebutuhan</p>
</footer>

</body>
</html>
# PASSMAGRINDA-
