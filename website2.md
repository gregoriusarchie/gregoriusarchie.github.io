<!DOCTYPE html> 
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2f;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #2a2a3d;
        }
        .logo-container {
            display: flex;
            align-items: center;
        }
        .logo-img {
            height: 50px;
            margin-right: 15px;
        }
        .website-name {
            margin: 0;
            font-size: 1.5em;
        }
        .horizontal-nav {
            background-color: #3a3a4d;
            padding: 10px;
        }
        .nav-list {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
            justify-content: center;
        }
        .nav-item {
            margin: 0 15px;
        }
        .nav-link {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .hero {
            text-align: center;
            padding: 40px 20px;
            margin-bottom: 30px;
        }
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        .feature-card {
            background-color: #2a2a3d;
            padding: 20px;
            border-radius: 8px;
            cursor: pointer;
            transition: transform 0.3s;
        }
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        h1, h2, h3 {
            color: #ffcc00;
        }
        footer {
            background-color: #2a2a3d;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        a {
            color: #ffcc00;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-container">
            <div class="logo-container">
                <!-- Using relative path for GitHub compatibility -->
                <img src="images/ES7-removebg-preview.png" alt="Logo" class="logo-img">
                <h1 class="website-name">Epic 7 GlOBAL</h1>
            </div>
        </div>
        <nav class="horizontal-nav">
            <ul class="nav-list">
                <li class="nav-item"><a href="tentangkami.html" class="nav-link">Tentang Kami</a></li>
                <li class="nav-item"><a href="layanan.html" class="nav-link">Layanan</a></li>
                <li class="nav-item"><a href="kontak.html" class="nav-link">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Selamat Datang di Website Kami</h1>
            <p>Hai, selamat datang di website kami! Senang banget kamu mampir. Yuk, jelajahi dan temukan hal-hal seru di sini!</p>
        </section>

        <section class="features">
            <div class="feature-card" onclick="navigateTo('services.html#feature1')">
                <h3>Story Mode</h3>
                <p>Epic Seven memiliki cerita yang mendalam dan menarik, dengan berbagai chapter dan episode 
                   yang bisa kamu jelajahi.Setiap karakter memiliki latar belakang dan cerita unik yang memperkaya pengalaman bermain.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature2')">
                <h3>Hero Collection</h3>
                <p>Kamu bisa mengumpulkan berbagai hero dengan kemampuan dan elemen yang berbeda.Setiap hero memiliki skill yang unik dan bisa di-upgrade untuk meningkatkan kekuatan mereka.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>PvP Arena</h3>
                <p>Di sini, kamu bisa bertarung melawan pemain lain dari seluruh dunia. Arena PvP menawarkan tantangan yang kompetitif dan hadiah menarik bagi para pemenang.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Guilds</h3>
                <p>Bergabung dengan guild memungkinkan kamu untuk berinteraksi dengan pemain lain, berpartisipasi dalam guild wars, dan mendapatkan berbagai keuntungan serta hadiah eksklusif.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Labyrinth</h3>
                <p>Labyrinth adalah mode permainan di mana kamu bisa menjelajahi dungeon yang penuh dengan musuh dan harta karun. Setiap level memiliki tantangan yang berbeda dan membutuhkan strategi yang baik untuk diselesaikan.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Hunt</h3>
                <p>Mode ini memungkinkan kamu untuk berburu monster kuat untuk mendapatkan material yang diperlukan untuk crafting gear dan equipment yang lebih baik.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Crafting</h3>
                <p>Kamu bisa membuat berbagai macam gear dan equipment dengan material yang kamu dapatkan dari berbagai mode permainan. Crafting memungkinkan kamu untuk menyesuaikan perlengkapan sesuai dengan kebutuhan hero kamu.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Side Stories</h3>
                <p>Selain cerita utama, Epic Seven juga memiliki side stories yang memberikan latar belakang tambahan tentang karakter dan dunia dalam game. Ini juga sering kali disertai dengan event dan hadiah khusus.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Automaton Tower</h3>
                <p>Ini adalah mode permainan di mana kamu harus mendaki menara dengan tingkat kesulitan yang semakin meningkat. Setiap lantai menawarkan tantangan unik dan hadiah yang berharga.</p>
            </div>
            <div class="feature-card" onclick="navigateTo('services.html#feature3')">
                <h3>Expedition</h3>
                <p>Mode ini memungkinkan kamu untuk mengirim hero dalam misi ekspedisi untuk mendapatkan berbagai hadiah. Ini adalah cara yang baik untuk mendapatkan resource tambahan tanpa harus bermain secara aktif.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Epic 7 Seven Global. Semua hak dilindungi.</p>
    </footer>

    <script>
        function navigateTo(url) {
            window.location.href = url;
        }
    </script>
</body> 
</html>
