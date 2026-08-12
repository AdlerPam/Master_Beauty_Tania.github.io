<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tania Beauty Studio — Чернівці</title>
    <style>
        /* Стильний б'юті-фон та базові налаштування тексту */
        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: #fcf8f7; /* Трендовий пастельно-нюдовий фон */
            color: #4a3e3d; /* М'який темний колір для гарного читання */
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* Головний контейнер сторінки */
        .container {
            max-width: 500px; /* Ідеальна ширина для перегляду з телефона */
            margin: 0 auto;
            padding: 25px 15px;
            background-color: #ffffff; /* Біла картка для контенту */
            box-shadow: 0 4px 15px rgba(220, 195, 190, 0.3);
            border-radius: 20px;
            margin-top: 20px;
            margin-bottom: 20px;
        }

        /* Шапка сайту */
        header {
            text-align: center;
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 26px;
            letter-spacing: 2px;
            color: #8c6b65; /* Елегантний рожево-коричневий відтінок */
            margin-bottom: 5px;
            text-transform: uppercase;
        }

        header p {
            font-style: italic;
            color: #aa908b;
            margin-top: 0;
            font-size: 15px;
        }

        /* Розділювачі секцій */
        hr {
            border: 0;
            height: 1px;
            background: #f0e2df;
            margin: 25px 0;
        }

        /* Секція послуг та прайсу */
        .price-section h2 {
            font-size: 19px;
            color: #8c6b65;
            border-left: 3px solid #dfbca0;
            padding-left: 10px;
            margin-bottom: 15px;
        }

        .price-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .price-item {
            display: flex;
            justify-content: space-between;
            padding: 8px 0;
            border-bottom: 1px dashed #f2eae8;
            font-size: 15px;
        }

        .price-name {
            font-weight: 500;
        }

        .price-cost {
            font-weight: bold;
            color: #8c6b65;
        }

        /* Портфоліо / Галерея робіт */
        .portfolio-section h2 {
            font-size: 19px;
            color: #8c6b65;
            text-align: center;
            margin-bottom: 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr; /* Фото ставатимуть по 2 в ряд */
            gap: 12px;
            margin-bottom: 15px;
        }

        .grid-item {
            background-color: #fcf8f7;
            border-radius: 12px;
            overflow: hidden;
            text-align: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.03);
        }

        .grid-item img {
            width: 100%;
            height: 180px;
            object-fit: cover; /* Обрізає фото акуратно по квадрату */
            display: block;
        }

        .grid-item span {
            display: block;
            font-size: 12px;
            padding: 6px 4px;
            color: #8a7370;
        }

        /* Трендові кнопки для соцмереж та месенджерів */
        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 14px;
            margin-bottom: 12px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 600;
            font-size: 15px;
            transition: transform 0.2s;
        }

        .btn:active {
            transform: scale(0.98);
        }

        .btn-instagram {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
            color: white;
        }

        .btn-telegram {
            background-color: #229ED9;
            color: white;
        }

        .btn-viber {
            background-color: #7360f2;
            color: white;
        }

        .btn-phone {
            background-color: #4ae082;
            color: white;
        }

        .location-info {
            text-align: center;
            font-size: 14px;
            color: #7a6663;
            background-color: #fefbfb;
            padding: 12px;
            border-radius: 10px;
            border: 1px solid #f5eae8;
        }
    </style>
</head>
<body>

<div class="container">

    <!-- Шапка сайту -->
    <header>
        <h1>✨ TANIA BEAUTY ✨</h1>
        <p>Студія краси у м. Чернівці</p>
    </header>

    <!-- Секція Прайсу -->
    <div class="price-section">
        <h2>💅 Манікюр та Педикюр</h2>
        <ul class="price-list">
            <li class="price-item"><span class="price-name">Гігієнічний манікюр</span><span class="price-cost">200 грн</span></li>
            <li class="price-item"><span class="price-name">Манікюр + покриття гель-лаком</span><span class="price-cost">450_грн</span></li>
            <li class="price-item"><span class="price-name">Нарощування нігтів</span><span class="price-cost">600 грн</span></li>
            <li class="price-item"><span class="price-name">Естетичний педикюр</span><span class="price-cost">500 грн</span></li>
        </ul>
    </div>

    <div class="price-section" style="margin-top: 20px;">
        <h2>👁️ Оформлення брів та Вії</h2>
        <ul class="price-list">
            <li class="price-item"><span class="price-name">Корекція + фарбування брів</span><span class="price-cost">250 грн</span></li>
            <li class="price-item"><span class="price-name">Ламінування брів</span><span class="price-cost">350_грн</span></li>
            <li class="price-item"><span class="price-name">Ламінування вій</span><span class="price-cost">400 грн</span></li>
            <li class="price-item"><span class="price-name">Нарощування вій (класика / 2D)</span><span class="price-cost">500/600 грн</span></li>
        </ul>
    </div>

    <hr>

    <!-- Секція Портфоліо з фотографіями -->
    <div class="portfolio-section">
        <h2>📸 Портфоліо робіт</h2>
        
        <div class="grid">
            <!-- Перше фото (Ваш файл Work1.jfif) -->
            <div class="grid-item">
                <img src="Work1.jfif" alt="Манікюр Чернівці">
                <span>Ніжний манікюр</span>
            </div>
            <!-- Місце для другого фото (завантажте файл як Work2.jfif або змініть назву нижче) -->
            <div class="grid-item">
                <img src="Work2.jfif" alt="Брови Чернівці">
                <span>Ідеальні брови</span>
            </div>
            <!-- Місце для третього фото -->
            <div class="grid-item">
                <img src="Work3.jfif" alt="Педикюр Чернівці">
                <span>Педикюр</span>
            </div>
            <!-- Місце для четвертого фото -->
            <div class="grid-item">
                <img src="Work4.jfif" alt="Вії Чернівці">
                <span>Виразний погляд</span>
            </div>
        </div>
    </div>

    <hr>

    <!-- Локація -->
    <div class="price-section">
        <h2>📍 Де я перебуваю?</h2>
        <div class="location-info">
            <strong>📍 м. Чернівці</strong><br>
            [Вкажіть тут ваш район, вулицю або назву салону]
        </div>
    </div>

    <hr>

    <!-- Кнопки швидкого зв'язку -->
    <div class="price-section">
        <h2 style="text-align: center;">📅 Записатись на процедуру</h2>
        
        <!-- Замініть посилання на свої профілі та номер телефону -->
        <a href="https://instagram.com" class="btn btn-instagram" target="_blank">📸 Мій Instagram</a>
        <a href="https://t.me" class="btn btn-telegram" target="_blank">💬 Написати у Telegram</a>
        <a href="https://viber.click" class="btn btn-viber" target="_blank">💜 Написати у Viber</a>
        <a href="tel:+380XXXXXXXXX" class="btn btn-phone">📞 Зателефонувати</a>
    </div>

</div>

</body>
</html>
