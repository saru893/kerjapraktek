<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Press Release - PT Teknologi Maju Indonesia</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.7;
            color: #1a1a1a;
            background: #fafafa;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
        }

        .header {
            background: white;
            border-bottom: 3px solid #0066cc;
            padding: 50px 40px 40px;
        }

        .company-logo {
            text-align: center;
            margin-bottom: 25px;
        }

        .company-logo h1 {
            font-size: 1.8em;
            color: #0066cc;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .company-tagline {
            text-align: center;
            color: #666;
            font-size: 0.95em;
            margin-bottom: 30px;
        }

        .press-badge {
            background: #0066cc;
            color: white;
            display: inline-block;
            padding: 8px 24px;
            border-radius: 4px;
            font-weight: 600;
            letter-spacing: 0.5px;
            font-size: 0.85em;
            text-transform: uppercase;
        }

        .content {
            padding: 40px;
        }

        .meta-info {
            display: flex;
            flex-wrap: wrap;
            gap: 25px;
            padding: 20px 0;
            margin-bottom: 30px;
            border-top: 1px solid #e5e5e5;
            border-bottom: 1px solid #e5e5e5;
            font-size: 0.9em;
        }

        .meta-item {
            display: flex;
            align-items: center;
            gap: 8px;
            color: #666;
        }

        .meta-item strong {
            color: #1a1a1a;
            font-weight: 600;
        }

        .headline {
            font-size: 2.2em;
            color: #1a1a1a;
            margin-bottom: 20px;
            line-height: 1.25;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .subheadline {
            font-size: 1.25em;
            color: #4a4a4a;
            margin-bottom: 35px;
            font-weight: 400;
            line-height: 1.5;
        }

        .dateline {
            font-weight: 600;
            color: #1a1a1a;
            margin-bottom: 5px;
        }

        .body-text {
            font-size: 1.05em;
            color: #333;
            margin-bottom: 20px;
            line-height: 1.8;
        }

        .body-text p {
            margin-bottom: 22px;
        }

        .body-text p:first-of-type::first-letter {
            font-size: 3.5em;
            font-weight: 700;
            float: left;
            line-height: 0.9;
            margin: 8px 10px 0 0;
            color: #0066cc;
        }

        .quote-section {
            background: #f8f9fa;
            border-left: 4px solid #0066cc;
            padding: 30px 35px;
            margin: 35px 0;
            position: relative;
        }

        .quote-section::before {
            content: '"';
            font-size: 4em;
            color: #0066cc;
            opacity: 0.2;
            position: absolute;
            top: 10px;
            left: 10px;
            font-family: Georgia, serif;
        }

        .quote-text {
            font-size: 1.15em;
            color: #2c2c2c;
            line-height: 1.7;
            margin-bottom: 15px;
            font-style: italic;
        }

        .quote-author {
            font-style: normal;
            font-weight: 600;
            color: #0066cc;
            font-size: 0.95em;
        }

        .quote-author-title {
            color: #666;
            font-weight: 400;
            font-size: 0.9em;
        }

        .highlight-box {
            background: #f5f9ff;
            border: 1px solid #d6e8ff;
            padding: 30px;
            border-radius: 6px;
            margin: 35px 0;
        }

        .highlight-box h3 {
            color: #0066cc;
            margin-bottom: 20px;
            font-size: 1.3em;
            font-weight: 600;
        }

        .highlight-box ul {
            list-style: none;
            padding-left: 0;
        }

        .highlight-box li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
            color: #333;
            line-height: 1.6;
        }

        .highlight-box li:before {
            content: "•";
            position: absolute;
            left: 10px;
            color: #0066cc;
            font-weight: bold;
            font-size: 1.5em;
        }

        .about-section {
            background: #fafafa;
            padding: 30px;
            margin: 40px 0;
            border-radius: 6px;
            border: 1px solid #e5e5e5;
        }

        .about-section h3 {
            color: #1a1a1a;
            margin-bottom: 15px;
            font-size: 1.2em;
            font-weight: 600;
        }

        .about-section p {
            color: #4a4a4a;
            line-height: 1.7;
        }

        .divider {
            height: 1px;
            background: #e5e5e5;
            margin: 35px 0;
        }

        .article-image {
            margin: 30px 0;
            text-align: center;
        }

        .article-image img {
            width: 100%;
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .image-caption {
            margin-top: 12px;
            font-size: 0.9em;
            color: #666;
            font-style: italic;
            line-height: 1.5;
        }

        .contact-section {
            background: #f8f9fa;
            padding: 40px;
            border-top: 1px solid #e5e5e5;
        }

        .contact-section h3 {
            margin-bottom: 25px;
            font-size: 1.4em;
            color: #1a1a1a;
            font-weight: 600;
        }

        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: 12px;
        }

        .contact-icon {
            width: 40px;
            height: 40px;
            background: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2em;
            flex-shrink: 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .contact-details {
            flex: 1;
        }

        .contact-details strong {
            display: block;
            color: #1a1a1a;
            margin-bottom: 5px;
            font-weight: 600;
        }

        .contact-details a {
            color: #0066cc;
            text-decoration: none;
            transition: color 0.3s;
        }

        .contact-details a:hover {
            color: #004999;
            text-decoration: underline;
        }

        .contact-details .role {
            color: #666;
            font-size: 0.9em;
        }

        .related-posts {
            padding: 50px 40px;
            background: white;
            border-top: 1px solid #e5e5e5;
        }

        .related-posts h3 {
            font-size: 1.8em;
            color: #1a1a1a;
            margin-bottom: 35px;
            font-weight: 600;
            position: relative;
            padding-bottom: 15px;
        }

        .related-posts h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 60px;
            height: 3px;
            background: #0066cc;
        }

        .posts-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .post-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            border: 1px solid #e5e5e5;
            transition: all 0.3s ease;
            text-decoration: none;
            display: block;
        }

        .post-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.12);
            border-color: #0066cc;
        }

        .post-image {
            width: 100%;
            height: 200px;
            overflow: hidden;
            background: #f0f0f0;
        }

        .post-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s;
        }

        .post-card:hover .post-image img {
            transform: scale(1.05);
        }

        .post-content {
            padding: 25px;
        }

        .post-category {
            display: inline-block;
            background: #e8f2ff;
            color: #0066cc;
            padding: 5px 14px;
            border-radius: 4px;
            font-size: 0.8em;
            font-weight: 600;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .post-title {
            font-size: 1.15em;
            color: #1a1a1a;
            font-weight: 600;
            margin-bottom: 12px;
            line-height: 1.4;
        }

        .post-excerpt {
            font-size: 0.9em;
            color: #666;
            line-height: 1.6;
            margin-bottom: 15px;
        }

        .post-meta {
            display: flex;
            align-items: center;
            justify-content: space-between;
            font-size: 0.85em;
            color: #999;
            padding-top: 15px;
            border-top: 1px solid #f0f0f0;
        }

        .post-date {
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .read-more {
            color: #0066cc;
            font-weight: 600;
            display: inline-flex;
            align-items: center;
            gap: 5px;
            transition: gap 0.3s;
        }

        .post-card:hover .read-more {
            gap: 8px;
        }

        .footer {
            text-align: center;
            padding: 30px 20px;
            background: #2c2c2c;
            color: #aaa;
            font-size: 0.9em;
        }

        .footer-end {
            margin-top: 15px;
            padding-top: 15px;
            border-top: 1px solid #444;
            color: #888;
        }

        @media (max-width: 768px) {
            .container {
                margin: 20px;
            }

            .header {
                padding: 30px 25px 25px;
            }

            .company-logo h1 {
                font-size: 1.5em;
            }

            .content {
                padding: 25px;
            }

            .headline {
                font-size: 1.7em;
            }

            .subheadline {
                font-size: 1.1em;
            }

            .meta-info {
                flex-direction: column;
                gap: 12px;
            }

            .contact-info {
                grid-template-columns: 1fr;
            }

            .posts-grid {
                grid-template-columns: 1fr;
            }

            .related-posts {
                padding: 40px 25px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <!-- Content -->
        <div class="content">
            <!-- Meta Information -->

            <!-- Headline -->
            <h2 class="headline">Mahasiswa Teknik Informatika UNPAM Laksanakan KP Kembangkan Sistem Ujian Online Berbasis Web di Yayasan Baitul Mukhlishin</h2>

            <!-- Subheadline -->

            <p class="dateline">Tangerang-Selatan, 17 Desember 2025</p>

            <!-- Body Text -->
            <div class="body-text">
                <p>Tangerang Selatan — Tiga mahasiswa Program Studi Teknik Informatika, yaitu Shahrudin, Gideon Triman Harefa, dan Dian Nurul Iman, dibimbing oleh dosen Pak Maulana Ardhiansyah, S.Kom., M.Kom., dari Universitas Pamulang, telah melaksanakan kegiatan Kerja Praktek (KP) di SMP Islam Mumtaza pada periode 29 September hingga 4 Desember 2025. Kegiatan ini bertujuan untuk mendukung digitalisasi proses ujian sekolah melalui pengembangan sistem ujian berbasis web dengan penerapan metode AGILE.</p>

                <div class="article-image">
                    <img src="C:/Users/laptop/Documents/semester 6/Press release/img/Picture1.jpg" alt="Platform SmartBiz Dashboard">
                    <p class="image-caption">Dashboard utama platform SmartBiz yang menampilkan analitik bisnis real-time</p>
                </div>

                <p>SmartBiz menawarkan fitur-fitur komprehensif termasuk manajemen inventori otomatis, analisis prediktif untuk perencanaan bisnis, chatbot customer service berbasis AI, dan sistem akuntansi terintegrasi. Dalam uji coba selama enam bulan dengan 500 UMKM di Jabodetabek, platform ini terbukti meningkatkan efisiensi operasional rata-rata sebesar 40% dan mengurangi biaya operasional hingga 30%.</p>

                <div class="article-image">
                    <img src="https://via.placeholder.com/800x450/0066cc/ffffff?text=Gambar+2+-+Ganti+URL+Disini" alt="Fitur AI SmartBiz">
                    <p class="image-caption">Fitur asisten AI yang membantu pelaku UMKM dalam pengambilan keputusan bisnis</p>
                </div>

                <p>Peluncuran ini sejalan dengan komitmen pemerintah untuk mendorong digitalisasi UMKM sebagai bagian dari program Indonesia Digital 2025. Platform SmartBiz telah mendapat sertifikasi dari Kementerian Komunikasi dan Informatika serta dukungan dari Kementerian Koperasi dan UKM.</p>

                <div class="article-image">
                    <img src="https://via.placeholder.com/800x450/0066cc/ffffff?text=Gambar+3+-+Ganti+URL+Disini" alt="Peluncuran SmartBiz">
                    <p class="image-caption">Acara peluncuran platform SmartBiz yang dihadiri oleh perwakilan pemerintah dan pelaku UMKM</p>
                </div>
            </div>

            <!-- Quote Section -->
            <div class="quote-section">
                <div class="quote-text">"Kami percaya bahwa teknologi AI tidak harus rumit dan mahal. Dengan SmartBiz, kami menghadirkan solusi yang terjangkau dan mudah digunakan, sehingga setiap pelaku UMKM dapat merasakan manfaat transformasi digital. Ini adalah langkah strategis kami dalam mendukung pertumbuhan ekonomi nasional melalui pemberdayaan UMKM."</div>
                <div class="quote-author">Budi Santoso</div>
                <div class="quote-author-title">CEO & Founder, PT Teknologi Maju Indonesia</div>
            </div>

            <div class="body-text">
                <p>Platform ini menawarkan tiga paket berlangganan yang disesuaikan dengan skala usaha, mulai dari paket Basic untuk usaha mikro dengan harga Rp 99.000 per bulan, hingga paket Enterprise untuk usaha menengah dengan fitur kustomisasi penuh. Untuk mendukung adopsi awal, perusahaan menawarkan uji coba gratis selama 30 hari tanpa perlu kartu kredit.</p>

                <div class="article-image">
                    <img src="https://via.placeholder.com/800x450/0066cc/ffffff?text=Gambar+4+-+Ganti+URL+Disini" alt="Paket Berlangganan SmartBiz">
                    <p class="image-caption">Berbagai paket berlangganan SmartBiz yang disesuaikan dengan kebutuhan UMKM</p>
                </div>
            </div>

            <div class="divider"></div>

            <!-- Highlight Box -->
            <div class="highlight-box">
                <h3>Fitur Unggulan SmartBiz</h3>
                <ul>
                    <li>Dashboard analitik real-time dengan visualisasi data yang mudah dipahami</li>
                    <li>Asisten AI yang dapat menjawab pertanyaan bisnis dan memberikan rekomendasi strategis</li>
                    <li>Integrasi dengan marketplace populer seperti Tokopedia, Shopee, dan Bukalapak</li>
                    <li>Sistem notifikasi pintar untuk manajemen stok dan follow-up pelanggan</li>
                    <li>Laporan keuangan otomatis yang siap untuk pelaporan pajak</li>
                    <li>Aplikasi mobile untuk monitoring bisnis dari mana saja</li>
                </ul>
            </div>

            <div class="body-text">
                <p>PT Teknologi Maju Indonesia berencana mengadakan roadshow ke 15 kota besar di Indonesia sepanjang tahun 2026 untuk memberikan pelatihan gratis kepada pelaku UMKM. Perusahaan juga telah menggandeng berbagai asosiasi pengusaha dan inkubator bisnis untuk memperluas jangkauan program edukasi digital mereka.</p>

                <div class="article-image">
                    <img src="https://via.placeholder.com/800x450/0066cc/ffffff?text=Gambar+5+-+Ganti+URL+Disini" alt="Pelatihan UMKM">
                    <p class="image-caption">Sesi pelatihan penggunaan platform SmartBiz untuk pelaku UMKM</p>
                </div>

                <p>Platform SmartBiz kini telah tersedia dan dapat diakses melalui website resmi perusahaan. Pengguna baru yang mendaftar hingga akhir Januari 2026 akan mendapatkan bonus konsultasi bisnis gratis senilai Rp 2 juta dari tim ahli perusahaan.</p>
            </div>

            <div class="divider"></div>

            <!-- About Section -->
            <div class="about-section">
                <h3>Tentang PT Teknologi Maju Indonesia</h3>
                <p>PT Teknologi Maju Indonesia adalah perusahaan teknologi yang berfokus pada pengembangan solusi digital untuk memberdayakan UMKM di Indonesia. Didirikan pada tahun 2020, perusahaan telah melayani lebih dari 10.000 pelaku usaha di berbagai sektor industri. Dengan tim yang terdiri dari 150+ profesional di bidang AI, software development, dan business consulting, kami berkomitmen untuk menjadi mitra terpercaya dalam transformasi digital UMKM Indonesia. Untuk informasi lebih lanjut, kunjungi www.teknologimaju.co.id</p>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="contact-section">
            <h3>Kontak Media</h3>
            <div class="contact-info">
                <div class="contact-item">
                    <div class="contact-icon">👤</div>
                    <div class="contact-details">
                        <strong>Sarah Wijaya</strong>
                        <div class="role">Head of Public Relations</div>
                    </div>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">📧</div>
                    <div class="contact-details">
                        <strong>Email</strong>
                        <a href="mailto:media@teknologimaju.co.id">media@teknologimaju.co.id</a>
                    </div>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">📱</div>
                    <div class="contact-details">
                        <strong>Telepon</strong>
                        <a href="tel:+622150001234">+62 21 5000 1234</a>
                    </div>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">🌐</div>
                    <div class="contact-details">
                        <strong>Website</strong>
                        <a href="https://www.teknologimaju.co.id" target="_blank">www.teknologimaju.co.id</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Related Posts Section -->
        <div class="related-posts">
            <h3>Berita Terkait</h3>
            <div class="posts-grid">
                <!-- Post Card 1 -->
                <a href="https://portalbersama.com/2024/11/15/pelatihan-digital-oleh-mahasiswa-untuk-santri-dompet-yatim-dhuafa-langkah-maju-di-era-teknologi/" class="post-card" target="_blank">
                    <div class="post-image">
                        <img src="C:/Users/laptop/Documents/semester 6/Press release/img/1.jpg" alt="Judul Artikel 1">
                    </div>
                    <div class="post-content">
                        <span class="post-category">Teknologi</span>
                        <h4 class="post-title">Pelatihan Digital oleh Mahasiswa untuk Santri Dompet Yatim Dhuafa, Langkah Maju di Era Teknologi</h4>
                        <p class="post-excerpt">Tangerang Selatan, 15 November 2024 – Sekelompok mahasiswa menggelar kegiatan pengabdian kepada masyarakat berupa pelatihan “Pengenalan microsoft office dan cara pengoprasian kepada anak-anak di yayasan domyadhu guna menambah wawasan dan pengetahuan”. Kegiatan yang dilaksanakan pada 10 November 2024 di yayasan Dompet Yatim Dhuafa pamulang ini bertujuan meningkatkan keterampilan digital untuk para santri. Kelompok mahasiswa yang tergabung dalam program ini terdiri dari Moh. Rizki Kurniawan selaku ketua, Wahyu Hidayatulloh, Achmad Fatur Raja, Ravly Paixs Akbar, Selbi Rafi Arfansyah, Adrianus Gheru Dendo, Farhan Afiq Fauzan. Kegiatan ini turut dihadiri oleh perwakilan yayasan Dompet Yatim Dhuafa, Bapak Hendra Dariyadi, yang mengapresiasi…</p>
                        <div class="post-meta">
                            <span class="post-date">📅 15 November 2024</span>
                            <span class="read-more">Baca Artikel →</span>
                        </div>
                    </div>
                </a>

                <!-- Post Card 2 -->
                <a href="https://portalbersama.com/2024/07/01/mahasiswa-universitas-pamulang-rancang-sistem-rapor-online-untuk-smk-ti-dwiguna-depok/" class="post-card" target="_blank">
                    <div class="post-image">
                        <img src="C:/Users/laptop/Documents/semester 6/Press release/img/2.jpg" alt="Judul Artikel 2">
                    </div>
                    <div class="post-content">
                        <span class="post-category">Bisnis</span>
                        <h4 class="post-title">Mahasiswa Universitas Pamulang Rancang Sistem Rapor Online untuk SMK TI Dwiguna Depok</h4>
                        <p class="post-excerpt"> Depok, 1 Juli 2024 – Tiga mahasiswa Program Studi Teknik Informatika Fakultas Ilmu Komputer Universitas Pamulang berhasil merancang sistem rapor online untuk SMK TI Dwiguna, Kecamatan Cipayung, Kota Depok. Proyek ini merupakan bagian dari kegiatan Kerja Praktek yang dilaksanakan selama tiga bulan. Proyek ini melibatkan Gustiga Erwanike Agashi, Muhammad Hilmi M., dan Yudistira. Ketiganya merancang sistem yang bertujuan memudahkan proses penyampaian informasi nilai dan rapor kepada orang tua/wali murid secara online. Gustiga, salah satu mahasiswa yang terlibat, menjelaskan, “Dengan adanya sistem rapor online ini, diharapkan dapat meningkatkan efisiensi dan transparansi dalam pengelolaan data akademik siswa. Orang tua/wali murid…</p>
                        <div class="post-meta">
                            <span class="post-date">📅 1 Juli 2024</span>
                            <span class="read-more">Baca Artikel →</span>
                        </div>
                    </div>
                </a>

                <!-- Post Card 3 -->
                <a href="https://portalbersama.com/2024/11/21/mahasiswa-universitas-pamulang-gelar-pkm-di-sdn-cilandak-barat-12-tingkatkan-kewaspadaan-terhadap-ancaman-siber/" class="post-card" target="_blank">
                    <div class="post-image">
                        <img src="C:/Users/laptop/Documents/semester 6/Press release/img/3.jpg" alt="Judul Artikel 3">
                    </div>
                    <div class="post-content">
                        <span class="post-category">Inovasi</span>
                        <h4 class="post-title">Mahasiswa Universitas Pamulang Gelar PKM di SDN Cilandak Barat 12: Tingkatkan Kewaspadaan Terhadap Ancaman Siber</h4>
                        <p class="post-excerpt">Jakarta, 21 November 2024 – Tim mahasiswa Universitas Pamulang sukses melaksanakan program Pengabdian Kepada Masyarakat (PKM) bertema “Sosialisasi Menjaga Data dari Ancaman Siber di Era Digital” di SDN Cilandak Barat 12 pada tanggal 16 Oktober 2024. Program ini bertujuan memberikan edukasi kepada para guru tentang kewaspadaan terhadap ancaman siber yang semakin marak di era digital. Program ini dilaksanakan oleh mahasiswa Universitas Pamulang yang terdiri dari Christophorus Bayu Widyantoro selaku Ketua Pelaksana, dengan anggota Rivaldo Janter Tampubolon, Wendy Nur Arif, Irwan Hardi Kusuma, Novariman, Wahyu Aji Dwi Pangestu, Siska Wulandari, Imelda Januarisma, Panca Rio Nugroho, dan Zhaki Apriyan Zhodik.</p>
                        <div class="post-meta">
                            <span class="post-date">📅 21 November 2024</span>
                            <span class="read-more">Baca Artikel →</span>
                        </div>
                    </div>
                </a>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p><strong>### AKHIR ###</strong></p>
            <div class="footer-end">
                © 2025 PT Teknologi Maju Indonesia. Hak Cipta Dilindungi.
            </div>
        </div>
    </div>
</body>
</html>
