<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMK Negeri 1 Tangerang</title>
    <style>
        /* RESET */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #fff5f8;
            color: #444;
            line-height: 1.7;
        }

        /* NAVBAR */
        header {
            background-color: #ffffff;
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            box-shadow: 0 3px 12px rgba(220, 140, 170, 0.12);
            border-bottom: 3px solid #f8cbd9;
        }

        .logo {
            color: #d66b91;
            font-size: 21px;
            font-weight: bold;
        }

        nav {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #555;
            font-size: 14px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #dc7197;
        }

        .login {
            background-color: #f4b8cd;
            color: white;
            padding: 8px 20px;
            border-radius: 20px;
            text-decoration: none;
            font-weight: bold;
        }

        /* CONTAINER */
        .container {
            width: 92%;
            max-width: 1250px;
            margin: 30px auto;
        }

        /* GALERI BAGIAN ATAS */
        .gallery {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 18px;
            margin-bottom: 25px;
        }

        .main-image {
            height: 310px;
        }

        .small-gallery {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }

        .small-image {
            height: 147px;
        }

        .image-box {
            background: linear-gradient(135deg, #fce0e9, #f8c5d7);
            border: 2px solid #e9a5bd;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #bd6386;
            font-weight: bold;
            text-align: center;
            overflow: hidden;
            position: relative;
        }

        .image-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* BAGIAN BERITA */
        .content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 22px;
        }

        .news-column {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .news {
            background-color: white;
            border: 1px solid #f3cad8;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(210, 130, 160, 0.08);
        }

        .news h2 {
            color: #ce7093;
            font-size: 21px;
            margin-bottom: 5px;
        }

        .author {
            color: #999;
            font-size: 13px;
        }

        .date {
            text-align: right;
            color: #999;
            font-size: 13px;
            margin-bottom: 15px;
        }

        .news p {
            margin-bottom: 13px;
            text-align: justify;
            font-size: 14px;
        }

        .news h3 {
            color: #d47798;
            font-size: 16px;
            margin: 18px 0 8px;
        }

        .news ul {
            padding-left: 25px;
            margin-bottom: 15px;
            font-size: 14px;
        }

        .read-more {
            display: inline-block;
            background-color: #f4c1d2;
            color: #8e4560;
            padding: 8px 18px;
            text-decoration: none;
            border-radius: 20px;
            font-size: 13px;
            font-weight: bold;
            margin-top: 10px;
        }

        .read-more:hover {
            background-color: #e9a4bd;
            color: white;
        }

        /* SIDEBAR */
        .sidebar {
            background-color: white;
            border: 1px solid #f3cad8;
            border-radius: 12px;
            padding: 22px;
            box-shadow: 0 4px 15px rgba(210, 130, 160, 0.08);
        }

        .sidebar h3 {
            color: #ce7093;
            margin-bottom: 12px;
        }

        .sidebar a {
            display: block;
            text-decoration: none;
            color: #666;
            padding: 5px 0;
            font-size: 14px;
        }

        .sidebar a:hover {
            color: #d66b91;
            padding-left: 5px;
        }

        .sidebar-image {
            height: 180px;
            margin-top: 20px;
        }

        /* FOOTER */
        footer {
            background-color: #f4c1d2;
            color: #84445c;
            text-align: center;
            padding: 18px;
            margin-top: 30px;
            font-size: 14px;
            border-top: 3px solid #e9a4bd;
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            header {
                justify-content: center;
                gap: 15px;
            }

            nav {
                justify-content: center;
                gap: 12px;
            }

            .gallery {
                grid-template-columns: 1fr;
            }

            .main-image {
                height: 230px;
            }

            .small-image {
                height: 120px;
            }

            .content {
                grid-template-columns: 1fr;
            }

            .news {
                padding: 18px;
            }
        }

    </style>
</head>

<body>

<!-- NAVBAR -->
<header>
    <div class="logo">SMKN 1 TANGERANG</div>

    <nav>
        <a href="#">Beranda</a>
        <a href="#">Sekolah</a>
        <a href="#">Kurikulum</a>
        <a href="#">Kesiswaan</a>
        <a href="#">Humas</a>
        <a href="#">Sarana</a>
    </nav>

    <a href="#" class="login">Login</a>
</header>


<div class="container">

    <!-- GALERI GAMBAR -->
    <section class="gallery">

        <!-- DISINI GAMBAR 1 -->
        <div class="image-box main-image">
            <img src="https://website-sekolah-tugas-kelompok.pages.dev/image/cover.jpg"
            alt="Foto Sekolah">
        </div>

        <div class="small-gallery">

            <!-- DISINI GAMBAR 2 -->
            <div class="image-box small-image">
                <img src="https://i.pinimg.com/1200x/ad/9d/84/ad9d84af0cfa8cb42cbfd6497fa50493.jpg"
                alt="Logo Sekolah">
            </div>

            <!-- DISINI GAMBAR 3 -->
            <div class="image-box small-image">
                <img src="https://tangerangkota.go.id/assets/storage/files/banner/banner-images-20250911-1757587312.png"
                alt="Kegiatan PKK">
            </div>

            <!-- DISINI GAMBAR 4 -->
            <div class="image-box small-image">
                <img src="https://tangerangkota.go.id/assets/storage/files/photos/bank-foto-BVpmnmrgfy8FYywFCTT41786430755.jpeg"
                alt="Kunjungan TP PKK">
            </div>

            <!-- DISINI GAMBAR 5 -->
            <div class="image-box small-image">
                <img src="https://www.smkn1-tng.sch.id/wp-content/uploads/2024/07/ppdb-2024.jpg"
                alt="LAB SMKN 1">
            </div>

        </div>
    </section>


    <!-- BAGIAN UTAMA -->
    <section class="content">

        <!-- KOLOM BERITA -->
        <main class="news-column">

            <!-- BERITA PERTAMA -->
            <article class="news">

                <h2>SPMB SMA, SMK, dan SKh Negeri Banten Tahun 2026/2027 Resmi Diluncurkan</h2>

                <div class="author">Nama Pengarang: Adel</div>

                <div class="date">
                    Tangerang, 1 November 2026
                </div>

                <p>
                    Pemerintah Provinsi Banten resmi meluncurkan
                    Sistem Penerimaan Murid Baru (SPMB) untuk
                    jenjang SMA, SMK, dan SKh Negeri Tahun
                    Ajaran 2026/2027.
                </p>

                <p>
                    Kebijakan ini disusun untuk memastikan proses
                    penerimaan murid yang konsisten, efektif, dan
                    memudahkan seluruh pemangku kepentingan.
                </p>

                <p>Pelaksanaan SPMB di Banten mengacu pada:</p>

                <ul>
                    <li>Permendikdasmen No. 3 dan No. 9 Tahun 2025.</li>
                    <li>SE Dirjen PAUD, Pendidikan Dasar dan Menengah No. 0301/C/HK.04.01/2026 tentang SPMB 2026/2027.</li>
                    <li>Kepgub Banten No. 141 Tahun 2026 terkait Petunjuk Teknis SPMB SMA, SMK, dan SKh di Banten.</li>
                </ul>

                <h3>Mekanisme Seleksi SMK</h3>

                <p>
                    Berbeda dengan SMA, seleksi SMK Negeri
                    menitikberatkan pada rata-rata nilai rapor
                    5 semester akhir dengan bobot 30%, tes
                    kemampuan akademik 20%, serta tes minat
                    dan bakat 50%.
                </p>

                <p>
                    Seleksi SMK harus memprioritaskan calon
                    siswa yang berasal dari keluarga tidak
                    mampu/penyandang disabilitas sekitar 15%.
                </p>

                <p>
                    Memprioritaskan calon siswa dengan domisili
                    terdekat dari sekolah sekitar 10%.
                </p>

                <p>
                    Calon murid SMK dapat memilih dua konsentrasi
                    keahlian dalam satu sekolah.
                </p>

                <p>
                    Sementara itu, untuk Sekolah Khusus (SKh),
                    pendaftaran dilakukan secara luring
                    (langsung ke sekolah).
                </p>

                <h3>Jadwal Penting yang Wajib Dicatat</h3>

                <p>
                    Proses SPMB diawali dengan tahap Pra SPMB
                    pada 20 April hingga 31 Mei 2026 melalui
                    situs spmb.bantenprov.go.id untuk validasi
                    data awal.
                </p>

                <p>
                    Berikut adalah rangkaian jadwal pendaftaran SMA:
                </p>

                <ul>
                    <li>Jalur Domisili Lingkungan Sekolah: 10–11 Juni 2026.</li>
                    <li>Jalur Domisili Wilayah: 17–18 Juni 2026.</li>
                    <li>Jalur Afirmasi: 22–23 Juni 2026.</li>
                    <li>Jalur Prestasi Akademik: 27–29 Juni 2026.</li>
                    <li>Jalur Prestasi Non-Akademik: 2–3 Juli 2026.</li>
                    <li>Jalur Mutasi: 7–8 Juli 2026.</li>
                </ul>

                <h3>Persyaratan Umum</h3>

                <p>
                    Secara umum, calon murid SMA dan SMK harus
                    berusia maksimal 21 tahun pada 1 Juli 2026
                    dan telah menyelesaikan pendidikan SMP
                    atau sederajat.
                </p>

                <p>
                    Khusus pendaftaran SMA dan SMK dilakukan
                    secara daring melalui portal resmi yang
                    telah disediakan Pemprov Banten.
                </p>

                <p>
                    Dengan sistem ini, Pemprov Banten berharap
                    seluruh calon murid mendapatkan akses
                    pendidikan yang adil dan transparan sesuai
                    dengan zonasi dan prestasi masing-masing.
                </p>

                <a href="#" class="read-more">Baca selengkapnya</a>

            </article>


            <!-- BERITA KEDUA -->
            <article class="news">

                <h2>Selamat dan Sukses untuk Murid Kelas XII!</h2>

                <div class="author">Nama Pengarang: Adel</div>

                <div class="date">
                    Tangerang, 1 November 2026
                </div>

                <p>
                    Hari yang dinanti akhirnya tiba. Dengan
                    penuh rasa bangga dan haru, kami segenap
                    keluarga besar SMK Negeri 1 Tangerang
                    mengucapkan selamat kepada seluruh murid
                    kelas XII atas keberhasilannya menyelesaikan
                    masa studi dengan penuh dedikasi, kerja
                    keras, dan semangat pantang menyerah.
                </p>

                <p>
                    Kelulusan ini bukanlah akhir dari perjalanan,
                    melainkan awal dari langkah baru menuju masa
                    depan yang lebih luas dan penuh tantangan.
                    Ilmu, keterampilan, dan pengalaman yang telah
                    diperoleh selama menempuh pendidikan di
                    sekolah ini diharapkan menjadi bekal berharga
                    dalam meraih cita-cita, baik di dunia kerja,
                    wirausaha, maupun melanjutkan pendidikan
                    ke jenjang yang lebih tinggi.
                </p>

                <p>
                    Teruslah berkarya, kembangkan potensi diri,
                    dan jadilah pribadi yang berintegritas.
                    Jaga nama baik almamater di mana pun berada,
                    serta tetaplah menjunjung tinggi nilai-nilai
                    yang telah ditanamkan selama menjadi bagian
                    dari keluarga besar sekolah ini.
                </p>

                <p>
                    Kami percaya, setiap dari kalian memiliki
                    jalan sukses masing-masing. Melangkahlah
                    dengan percaya diri, dan jangan pernah
                    berhenti belajar.
                </p>

                <a href="#" class="read-more">Baca selengkapnya</a>

            </article>

        </main>


        <!-- SIDEBAR KANAN -->
        <aside class="sidebar">

            <h3>Tautan Eksternal</h3>

            <!-- YOUTUBE DAN YAHOO TANPA LINK -->
            <a>YouTube</a>
            <a>Yahoo</a>

            <!-- INSTAGRAM -->
            <a href="https://www.instagram.com/Sereal.matcha/"
               target="_blank">
                Instagram: Sereal.matcha
            </a>


            <!-- DISINI GAMBAR 6 -->
            <div class="image-box sidebar-image">
                DISINI GAMBAR 6
            </div>

        </aside>

    </section>

</div>


<!-- FOOTER -->
<footer>
    &copy; Hak Cipta SMKN 1 Tangerang, 2026
</footer>

</body>
</html>
