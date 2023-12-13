# web_design
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Авторизація</title>
    <style>
        /* Стилі тут... */
    </style>
</head>
<body>
    <header>
        <h1>Авторизація</h1>
    </header>
    <section class="section">
        <form id="loginForm">
            <label for="username">Логін:</label>
            <input type="text" id="username" name="username" required>

            <label for="password">Пароль:</label>
            <input type="password" id="password" name="password" required>

            <button type="button" onclick="authenticateUser()">Увійти</button>
        </form>
    </section>

    <script>
        function authenticateUser() {
            var username = document.getElementById("username").value;
            var password = document.getElementById("password").value;



            if (username && password) {

                window.location.href = "головна_сторінка.html";
            } else {
                // Обробка невдачі аутентифікації (показ повідомлення про помилку тощо)
                alert("Будь ласка, введіть логін і пароль");
            }
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="uk">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Додаток для вивчення слів англійської мови</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }

        header {
            background-color: #4285f4;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        h1 {
            margin: 0;
        }

        section {
            margin: 20px 0;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #4285f4;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin-bottom: 8px;
        }

        button {
            background-color: #4285f4;
            color: white;
            padding: 8px 16px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

            button:hover {
                background-color: #3279d8;
            }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #4285f4;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Вивчення слів англійської мови</h1>
    </header>

    <section id="learning-section">
        <h2>Вправи для вивчення слів</h2>
        <div id="interactive-exercises">
            <!-- Додайте стилізовані блоки коду для вправ -->
            <div class="exercise">
                <h3>Вправа 1</h3>
                <p>Тест перевіряє базовий словниковий запас англійської мови на всіх рівнях</p>
                <button class="nav-link px-3" onclick="location.href='https://naurok.com.ua/test/start/2585456';" title="Онлайн тести">
                    Вибрати цю вправу
                </button>
            </div>
            <div class="exercise">
                <h3>Вправа 2</h3>
                <p>Тест перевіряє рівень володіння англійською мовою на всіх рівнях</p>
                <button class="nav-link px-3" onclick="location.href='https://naurok.com.ua/test/start/2585514';" title="Онлайн тести">
                    Вибрати цю вправу
            </div>
        </div>
    </section>

    <section id="resources-section">
        <h2>Корисні ресурси</h2>
        <p>Використовуйте ці ресурси для поглиблення знань:</p>
        <ul>
            <h2>Словник</h2>
            <li><a href="https://www.dict.com/%D0%B0%D0%BD%D0%B3%D0%BB%D1%96%D0%B8%D1%81%D1%8C%D0%BA%D0%BE-%D1%83%D0%BA%D1%80%D0%B0%D1%96%D0%BD%D1%81%D1%8C%D0%BA%D0%B8%D0%B8">Словник</a></li>
            <h2>Ігри для вивчення слів</h2>
            <li><a href="https://learning.ua/english/">Гра 1</a></li>
            <li><a href="https://uk.duolingo.com/course/en/uk/%D0%92%D0%B8%D0%B2%D1%87%D0%B0%D0%B0%D0%B9%D1%82%D0%B5-%D0%B0%D0%BD%D0%B3%D0%BB%D1%96%D0%B9%D1%81%D1%8C%D0%BA%D1%83">Гра 2</a></li>
            <h2>Відеоуроки</h2>
            <li><a href="https://youtu.be/Uc31tpOn0K4?si=4pIXFGCPBVIVrpoj">Відеоурок 1</a></li>
            <li><a href="https://youtu.be/lFqhffbf0G8?si=zXeBOvPW24Qy7Qbh">Відеоурок 2</a></li>
            <li><a href="https://www.youtube.com/watch?v=4L9oLCjN4DU">Відеоурок 3</a></li>
            <li><a href="https://www.youtube.com/watch?v=PkEvUGUjyP8">Відеоурок 4</a></li>
            <li><a href="https://www.youtube.com/watch?v=gBJDimxf__Q">Відеоурок 5</a></li>
            <li><a href="https://www.youtube.com/watch?v=Cfhs3q6WbSA">Відеоурок 6</a></li>
        </ul>
    </section>

    <footer>
        <p>Якщо виникли проблеми звертайтеся за номером +38(095)-964-36-18</p>
    </footer>

</body>
</html>


