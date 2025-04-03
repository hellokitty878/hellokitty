# hellokitty
<!DOCTYPE html>
<html lang="sr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mačke - Čudesni svet mačaka</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>🐱 Dobrodošli u svet mačaka 🐱</h1>
        <nav>
            <ul>
                <li><a href="#about">O mačkama</a></li>
                <li><a href="#facts">Zanimljivosti</a></li>
                <li><a href="#gallery">Galerija</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about" class="section">
            <h2>O mačkama</h2>
            <p>Mačke su jedne od najpopularnijih kućnih ljubimaca na svetu. One su inteligentne, znatiželjne i veoma umiljate.</p>
            <img src="https://placekitten.com/700/400" alt="Slatka mačka">
        </section>
        
        <section id="facts" class="section">
            <h2>Zanimljivosti o mačkama</h2>
            <button onclick="showFact()">🐾 Prikaži zanimljivost 🐾</button>
            <p id="cat-fact"></p>
        </section>
        
        <section id="gallery" class="section">
            <h2>Galerija mačaka</h2>
            <div class="gallery">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgmyTB_qmgq_q8m83WdZO7dqQqQyUU_Yeduw&s" alt="Mačka 1">
                <img src="data:image/jpeg;base64,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" alt="Mačka 2">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkTsCI73mCXVODI39cyPRYhyyfIMk296YWQA&s" alt="Mačka 3">
                 <img src="https://cdn-useast1.kapwing.com/static/templates/devastated-wet-cat-meme-maker-full-4f71f324.webp" alt="Mačka 4">
                 <img src="data:image/jpeg;base64,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" alt="Mačka 5">
                 <img src="data:image/jpeg;base64,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" alt="Mačka 6">
            </div>
        </section>
    </main>
    <footer id="contact">
        <p>&copy; 2025 Svet Mačaka | Kontakt: <a href="mailto:info@macke.rs">info@macke.rs</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
