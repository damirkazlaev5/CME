
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Смешарики</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: linear-gradient(135deg, #ff94b3, #ffd98e, #b5e48b);
            color: #222;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .container {
            width: 90%;
            max-width: 800px;
            margin: 30px auto;
            background: rgba(255, 255, 255, 0.96);
            border-radius: 25px;
            padding: 40px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.2);
        }
        h1 {
            text-align: center;
            color: #e64e5d;
            text-shadow: 4px 4px 0 #fff;
            font-size: 4rem;
            margin-bottom: 20px;
            animation: bounce 1s infinite alternate;
        }
        @keyframes bounce {
            from { transform: translateY(0); }
            to { transform: translateY(-10px); }
        }
        .subtitle {
            text-align: center;
            color: #6a5acd;
            font-size: 1.6rem;
            font-style: italic;
            margin-bottom: 30px;
        }
        p {
            margin-bottom: 20px;
            font-size: 1.3rem;
            line-height: 1.7;
        }
        .highlight {
            background-color: #ffd700;
            color: #8b0000;
            padding: 3px 10px;
            border-radius: 8px;
            font-weight: bold;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            color: white;
            font-size: 1.1rem;
            background: #8b0000;
            padding: 15px;
            border-radius: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🥕 Смешарики</h1>
        <p class="subtitle">Яркий мир круглых друзей!</p>
        
        <p>
            «Смешарики» — это <span class="highlight">увлекательный российский мультсериал</span>, 
            который любят дети и взрослые. Герои — круглые персонажи с уникальными характерами и историями.
        </p>
        <p>
            Каждый эпизод учит <span class="highlight">доброте</span>, <span class="highlight">дружбе</span>
            и <span class="highlight">решению проблем с юмором</span>.
        </p>
        <p>
            Сериал выходит с <span class="highlight">2004 года</span> и насчитывает сотни эпизодов.
            Среди героев: Крош, Ёжик, Нюша, Бараш, Лосяш, Копатыч, Совунья, Кар‑Карыч и Пин.
        </p>
        
        <footer>
            &copy; 2026 Фанатский сайт «Смешариков». Все права защищены.
        </footer>
    </div>
</body>
</html>
