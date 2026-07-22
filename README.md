# Nini-Indriyani_Website
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Tentang Saya</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #afbac9, #00f2fe);
            margin: 0;
            color: #333;
            transition: background 0.3s ease;
        }

        nav {
            background: #1a1c1f;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            cursor: pointer;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Dynamic Section Switching */
        .page-section {
            display: none;
        }

        .page-section.active {
            display: block;
        }

        /* Container Styles */
        .container {
            background: white;
            border-radius: 20px;
            padding: 30px;
        }

        /* Home Section Styles */
        #home .container {
            max-width: 900px;
            margin: 50px auto;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            text-align: center;
        }

        #home h1 {
            color: #0077b6;
            margin-bottom: 10px;
        }

        .tentang {
            text-align: justify;
            line-height: 1.8;
            font-size: 16px;
        }

        .footer-text {
            margin-top: 25px;
            color: #666;
            font-size: 14px;
        }

        /* Contact Section Styles */
        #contact .container {
            max-width: 700px;
            margin: 50px auto;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            margin-bottom: 20px;
            border-radius: 10px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }

        button {
            background: #2d7be5;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }

        /* About Section Styles */
        #about .container {
            max-width: 1000px;
            margin: 40px auto;
        }

        .profile {
            text-align: center;
        }

        .profile img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid #2d7be5;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 15px;
            margin-top: 25px;
        }

        .gallery img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            border-radius: 15px;
        }

        video {
            width: 80%;
            max-width: 400px;
            border-radius: 15px;
        }

        .video-section {
            text-align: center;
            margin-top: 40px;
        }

        /* Global Footer Styles */
        footer.global-footer {
            text-align: center;
            padding-bottom: 20px;
        }
    </style>
</head>
<body>

    <!-- Menu Navigasi (Contact dipindah ke paling kanan) -->
    <nav>
        <a href="#home" onclick="showPage('home')">🏠 Home</a>
        <a href="#about" onclick="showPage('about')">👤 About Me</a>
        <a href="#contact" onclick="showPage('contact')">📞 Contact</a>
    </nav>

    <!-- HALAMAN 1: HOME -->
    <div id="home" class="page-section active">
        <div class="container">
            <h1>Nini Indriyani</h1>
            <div class="tentang">
                <p>
                    Halo, saya <b>Nini Indriyani</b>. Saya merupakan mahasiswa
                    <b>Politeknik Pembangunan Pertanian Gowa</b> pada program studi
                    <b>Penyuluhan Peternakan dan Kesejahteraan Hewan</b>. Saya memiliki minat yang besar terhadap dunia peternakan, khususnya dalam bidang penyuluhan, manajemen usaha peternakan, serta pemberdayaan masyarakat pedesaan.
                </p>

                <p>Ketertarikan saya terhadap dunia peternakan berawal dari kondisi ternak yang dimiliki oleh orang tua saya. Saya melihat bahwa usaha ternak tersebut memiliki potensi yang besar untuk berkembang, namun pengelolaannya masih belum dilakukan secara optimal, baik dalam hal manajemen pemeliharaan, pemberian pakan, kesehatan ternak, maupun pencatatan usaha. Kondisi tersebut mendorong saya untuk mempelajari ilmu peternakan secara lebih mendalam agar di masa depan saya dapat membantu memperbaiki dan mengembangkan ternak keluarga menjadi lebih terarah, produktif, dan mampu memberikan hasil yang lebih baik bagi kesejahteraan keluarga.</p>

                <p>Selain itu, saya juga tertarik pada kegiatan penyuluhan karena saya percaya bahwa ilmu yang dimiliki akan lebih bermanfaat apabila dapat dibagikan kepada masyarakat. Saya ingin berperan dalam mendampingi petani dan peternak agar mampu menerapkan teknologi dan inovasi yang tepat sehingga produktivitas usaha mereka dapat meningkat dan kesejahteraan keluarga petani maupun peternak menjadi lebih baik.</p>

                <p>Selama menjalani pendidikan di <b>Politeknik Pembangunan Pertanian Gowa</b>, saya memperoleh berbagai pengalaman akademik dan praktik lapangan yang membantu saya memahami kondisi nyata di masyarakat. Pengalaman tersebut mengajarkan saya pentingnya kerja keras, disiplin, tanggung jawab, komunikasi yang baik, serta kemampuan bekerja sama dalam tim untuk mencapai tujuan bersama.</p>

                <p>Bagi saya, setiap pengalaman adalah kesempatan untuk belajar dan berkembang menjadi pribadi yang lebih baik. Saya percaya bahwa dengan semangat belajar, ketekunan, dan niat untuk memberikan manfaat bagi orang lain, saya dapat terus meningkatkan kemampuan diri dan berkontribusi dalam pembangunan sektor pertanian dan peternakan di masa depan. Saya berharap dapat menjadi pribadi yang tidak hanya sukses dalam bidang yang saya tekuni, tetapi juga mampu memberikan dampak positif bagi keluarga, masyarakat, serta dunia pertanian dan peternakan Indonesia.</p>
            </div>

            <div class="footer-text">
                © 2026 - Website Pribadi Nini Indriyani
            </div>
        </div>

        <hr>
        <footer class="global-footer">
            <p>Copyright &copy; 2026 Nini Indriyani.</p>
        </footer>
    </div>

    <!-- HALAMAN 2: ABOUT ME -->
    <div id="about" class="page-section">
        <div class="container">
            <h1><center>Nini Indriyani</center></h1>
            <h2><center>Kelas 3E NIM.05.03.23.3061</center></h2>
            <p><center>Mahasiswa Politeknik Pembangunan Pertanian Gowa</center></p>

            <h2>Foto Favorit Saya</h2>

            <div class="gallery">
                <img src="https://cdn.phototourl.com/free/2026-07-22-d3c09a42-5389-449b-bb3f-23f8462f57be.jpg" alt="Foto 1">
                <img src="https://cdn.phototourl.com/free/2026-07-22-121fdd5b-9a41-45bf-8ce1-28a6e23d309a.jpg" alt="Foto 2">
                <img src="https://cdn.phototourl.com/free/2026-07-22-70acf1c2-44a9-45e5-a4b8-3d1dc05b4aaf.jpg" alt="foto 3">
            </div>
            <p>Foto di atas merupakan pengalaman pertama saya melakukan kegiatan penyuluhan di depan banyak orang, yang menjadi momen sangat berharga dalam perjalanan pendidikan saya sebagai mahasiswa Penyuluhan Peternakan dan Kesejahteraan Hewan. Pengalaman ini tidak hanya melatih keberanian dan rasa percaya diri, tetapi juga meningkatkan kemampuan berkomunikasi, menyampaikan informasi secara jelas, serta berinteraksi dengan masyarakat.</p>

            <div class="video-section">
                <h2>Video Tentang Saya</h2>

                <video controls>
                    <source src="C:\Users\ACER\Downloads\WhatsApp Video 2026-07-22 at 15.49.33(1).mp4" type="video/mp4">
                </video>

                <p>
                    Video ini berisi pengalaman praktik lapangan saya dalam kegiatan penyuluhan di Desa Carigading, Kecamatan Awangpone, Kabupaten Bone dengan judul pemanfaatan jerami padi sebagai pakan fermentasi ternak.
                </p>
            </div>
        </div>

        <hr>
        <footer class="global-footer">
            <p>Copyright &copy; 2026 Nini Indriyani.</p>
        </footer>
    </div>

    <!-- HALAMAN 3: CONTACT (Di posisi paling akhir) -->
    <div id="contact" class="page-section">
        <div class="container">
            <h1>Hubungi Saya</h1>

            <form>
                <label for="insta"><b>Instagram:</b></label>
                <input type="text" id="insta" placeholder="@indriynii17_">

                <label for="kampus"><b>Status / Kampus:</b></label>
                <input type="text" id="kampus" placeholder="Mahasiswi Polbangtan Gowa">
            </form>
        </div>

        <hr>
        <footer class="global-footer">
            <p>Copyright &copy; 2026 Nini Indriyani.</p>
        </footer>
    </div>

    <!-- Script Pengendali Perpindahan Halaman -->
    <script>
        function showPage(pageId) {
            // Sembunyikan semua bagian halaman
            var sections = document.querySelectorAll('.page-section');
            sections.forEach(function(section) {
                section.classList.remove('active');
            });

            // Tampilkan bagian halaman yang dipilih
            var targetSection = document.getElementById(pageId);
            if (targetSection) {
                targetSection.classList.add('active');
            }

            // Sesuaikan background dan judul dokumen
            if (pageId === 'home') {
                document.body.style.background = "linear-gradient(to right, #afbac9, #00f2fe)";
                document.title = "Home - Tentang Saya";
            } else if (pageId === 'about') {
                document.body.style.background = "#afbac9";
                document.title = "About Me";
            } else if (pageId === 'contact') {
                document.body.style.background = "#afbac9";
                document.title = "Contact";
            }
        }

        // Tangani perubahan hashtag pada URL (#home, #about, #contact)
        function handleHash() {
            var hash = window.location.hash.replace('#', '');
            if (['home', 'about', 'contact'].includes(hash)) {
                showPage(hash);
            } else {
                showPage('home');
            }
        }

        window.addEventListener('hashchange', handleHash);
        window.addEventListener('load', handleHash);
    </script>
</body>
</html>
