<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Абай Құнанбайұлы — қазақ халқының ұлы ақыны, ойшылы және философы. Бұл сайтта оның өмірі, шығармалары, нақыл сөздері және фотогалерея берілген.">
    <title>Абай Құнанбайұлы — Мини сайт</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Open Sans', sans-serif;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #fff;
            text-align: center;
            padding: 30px 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }

        header h1 {
            font-size: 2.5rem;
            color: #2c3e50;
        }

        nav {
            background-color: #3498db;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
            font-weight: 600;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: #2980b9;
        }

        section {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }

        h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            border-left: 4px solid #3498db;
            padding-left: 10px;
        }

        p {
            margin-bottom: 15px;
        }

        .portrait {
            display: block;
            margin: 20px auto;
            width: 100%;
            max-width: 400px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .quotes {
            display: grid;
            gap: 20px;
        }

        .quote {
            background: #fdfdfd;
            border-left: 4px solid #3498db;
            padding: 15px 20px;
            border-radius: 6px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.03);
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            transition: transform 0.5s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
            max-width: 500px;
            margin: auto;
        }

        input, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 1rem;
        }

        button {
            background-color: #3498db;
            color: #fff;
            border: none;
            padding: 10px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: 600;
            transition: background 0.3s;
        }

        button:hover {
            background-color: #2980b9;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #fff;
            color: #7f8c8d;
            border-top: 1px solid #eee;
            margin-top: 40px;
        }

        @media (max-width: 600px) {
            nav a {
                padding: 10px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Абай Құнанбайұлы</h1>
        <p>Қазақтың ұлы ақыны, ойшылы және ағартушысы</p>
    </header>

    <nav>
        <a href="#basty">Басты бет</a>
        <a href="#omirbayan">Өмірбаяны</a>
        <a href="#quotes">Нақыл сөздері</a>
        <a href="#works">Шығармалары</a>
        <a href="#gallery">Галерея</a>
        <a href="#contact">Кері байланыс</a>
    </nav>

    <section id="basty">
        <h2>Басты бет</h2>
        <img src="https://iaer.kz/cache/imagine/main_page_full/uploads/news/2024/08/09/66fe2fe14d058696012713.jpg" alt="Абай Құнанбайұлы портреті" class="portrait">
        <p><strong>Абай Құнанбайұлы</strong> (1845–1904) — қазақ халқының ұлы ақыны, ағартушысы және философы. Оның шығармалары қазақ қоғамының рухани дамуына үлкен әсер етті. Абайдың негізгі мұрасы — өлеңдері, қара сөздері және аудармалары.</p>
    </section>

    <section id="omirbayan">
        <h2>Өмірбаяны</h2>
        <p>Абай 1845 жылы қазіргі Шығыс Қазақстан облысы, Семей өңірінде дүниеге келген. Оның толық аты — Ибраһим Құнанбайұлы. Абай жас кезінен білімге құштар болып, медреседе және орыс мектебінде оқыған.</p>
        <p>Ол қазақ қоғамының артта қалушылығына сын көзбен қарап, елді еңбекке, білімге, адамгершілікке шақырды. Абайдың шығармалары мен қара сөздері халықты рухани және мәдени тұрғыдан жаңартуға бағытталды.</p>
    </section>

    <section id="quotes">
        <h2>Нақыл сөздері</h2>
        <div class="quotes">
            <div class="quote">"Адамның ақылы — байлығы, білімі — бағасы."</div>
            <div class="quote">"Жақсылық қылсаң, өзің үшін қыл."</div>
            <div class="quote">"Ғылым таппай мақтанба, орын таппай баптанба."</div>
            <div class="quote">"Еңбек етсең ерінбей, тояды қарның тіленбей."</div>
        </div>
    </section>

    <section id="works">
        <h2>Шығармалары</h2>
        <ul>
            <li>«Қара сөздер» — философиялық ой-толғаныстар жинағы;</li>
            <li>«Сегіз аяқ», «Қыс», «Жаз», «Күз» — табиғат пен адам өмірін суреттейтін өлеңдер;</li>
            <li>А.С. Пушкин, М. Лермонтов, И. Крылов шығармаларын қазақ тіліне аударған;</li>
            <li>Қазақ жазба әдебиетінің негізін қалаған тұлға.</li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Галерея</h2>
        <div class="gallery">
            <img src="https://abai.kz/content/uploads/2019/09/950754_1491985084_680_0_0.jpg" alt="Абай мұражайы, Семей">
            <img src="https://informburo.kz/storage/photos/141/6353c88bc3aad.jpg" alt="Абай ескерткіші, Астана">
            <img src="https://abaiuniversity.edu.kz/docs/novosti/smiQS.jpg" alt="Абай кесенесі, Жидебай">
            <img src="https://ticketon.kz/files/media/photo_336204.jpeg" alt="Абай атындағы опера және балет театры, Алматы">
        </div>
    </section>

    <section id="contact">
        <h2>Кері байланыс</h2>
        <form>
            <input type="text" placeholder="Атыңыз" required>
            <input type="email" placeholder="Электронды поштаңыз" required>
            <textarea rows="4" placeholder="Хабарламаңыз..."></textarea>
            <button type="submit">Жіберу</button>
        </form>
    </section>

    <footer>
        <p>© 2025 | Абай Құнанбайұлына арналған мини-сайт.</p>
    </footer>
</body>
</html>
