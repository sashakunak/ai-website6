<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Штучний Інтелект: Майбутнє вже тут</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="icon" href="assets/images/favicon.ico"> </head>
<body>
    <header class="header">
        <div class="container">
            <a href="#" class="logo">AI Insight</a>
            <nav class="main-nav">
                <ul>
                    <li><a href="#about">Про ШІ</a></li>
                    <li><a href="#applications">Застосування</a></li>
                    <li><a href="#news">Новини</a></li>
                    <li><a href="#ethics">Етика ШІ</a></li>
                    <li><a href="#contact">Контакти</a></li>
                </ul>
            </nav>
            <button class="nav-toggle" aria-label="Toggle navigation">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </div>
    </header>
    <main>
        <section class="hero-section" id="home">
            <div class="container">
                <h1>Штучний Інтелект: Розуміння та Інновації</h1>
                <p>Досліджуйте світ ШІ, його можливості та вплив на наше життя.</p>
                <a href="#about" class="btn">Дізнатися більше</a>
            </div>
        </section>
        <section class="about-section" id="about">
            <div class="container">
                <h2>Що таке Штучний Інтелект?</h2>
                <div class="grid-layout">
                    <div class="text-content">
                        <p>Штучний інтелект (ШІ) — це галузь комп'ютерних наук, що займається створенням машин, які можуть мислити, навчатися та вирішувати проблеми подібно до людини. Він охоплює широкий спектр технологій, включаючи машинне навчання, глибоке навчання, обробку природної мови та комп'ютерний зір.</p>
                        <p>Від простих алгоритмів до складних нейронних мереж, ШІ трансформує галузі від медицини до фінансів, автоматизуючи процеси та відкриваючи нові можливості.</p>
                    </div>
                    <div class="image-content">
                        <img src="assets/images/ai-concept.jpg" alt="Концепція Штучного Інтелекту">
                    </div>
                </div>
            </div>
        </section>
        <section class="applications-section" id="applications">
            <div class="container">
                <h2>Застосування ШІ</h2>
                <div class="card-grid">
                    <div class="card">
                        <h3>Медицина</h3>
                        <p>Діагностика захворювань, розробка ліків, персоналізована медицина.</p>
                    </div>
                    <div class="card">
                        <h3>Автомобілі</h3>
                        <p>Автономні транспортні засоби, системи допомоги водію, оптимізація маршрутів.</p>
                    </div>
                    <div class="card">
                        <h3>Фінанси</h3>
                        <p>Виявлення шахрайства, торговельні стратегії, управління ризиками.</p>
                    </div>
                    <div class="card">
                        <h3>Освіта</h3>
                        <p>Персоналізоване навчання, оцінювання, автоматизація адміністративних завдань.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="news-section" id="news">
            <div class="container">
                <h2>Останні Новини та Дослідження</h2>
                <article class="news-item">
                    <h3>Новий прорив у генеративному ШІ</h3>
                    <p class="date">20 травня 2025</p>
                    <p>Дослідники представили нову модель, здатну генерувати високоякісний контент...</p>
                    <a href="#" class="read-more">Читати далі</a>
                </article>
                <article class="news-item">
                    <h3>Етичні виклики в розробці ШІ</h3>
                    <p class="date">15 травня 2025</p>
                    <p>Дискусії щодо відповідальності та безпеки систем штучного інтелекту набирають обертів...</p>
                    <a href="#" class="read-more">Читати далі</a>
                </article>
                <a href="#" class="btn secondary-btn">Всі новини</a>
            </div>
        </section>
        <section class="contact-section" id="contact">
            <div class="container">
                <h2>Зв'язатися з Нами</h2>
                <form class="contact-form">
                    <input type="text" placeholder="Ваше ім'я" required>
                    <input type="email" placeholder="Ваш Email" required>
                    <textarea placeholder="Ваше повідомлення" rows="5"></textarea>
                    <button type="submit" class="btn">Надіслати</button>
                </form>
            </div>
        </section>
    </main>
    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 AI Insight. Всі права захищені.</p>
            <div class="social-links">
                <a href="#" aria-label="Facebook"><img src="assets/images/facebook-icon.svg" alt="Facebook"></a>
                <a href="#" aria-label="Twitter"><img src="assets/images/twitter-icon.svg" alt="Twitter"></a>
                <a href="#" aria-label="LinkedIn"><img src="assets/images/linkedin-icon.svg" alt="LinkedIn"></a>
            </div>
        </div>
    </footer>
    <script src="js/main.js"></script>
</body>
</html>
/* Змінні для кольорів та шрифтів */
:root {
    --primary-color: #007bff; /* Синій */
    --secondary-color: #6c757d; /* Сірий */
    --accent-color: #28a745; /* Зелений */
    --dark-bg: #212529; /* Темний фон */
    --light-bg: #f8f9fa; /* Світлий фон */
    --text-color: #343a40; /* Темний текст */
    --light-text-color: #e9ecef; /* Світлий текст */
    --border-color: #dee2e6; /* Колір рамки */

    --font-primary: 'Roboto', sans-serif;
}

/* Загальні стилі */
body {
    font-family: var(--font-primary);
    margin: 0;
    line-height: 1.6;
    color: var(--text-color);
    background-color: var(--light-bg);
    scroll-behavior: smooth;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

h1, h2, h3 {
    color: var(--dark-bg);
    margin-bottom: 20px;
}

p {
    margin-bottom: 15px;
}

a {
    color: var(--primary-color);
    text-decoration: none;
    transition: color 0.3s ease;
}

a:hover {
    color: #0056b3;
}

.btn {
    display: inline-block;
    background-color: var(--primary-color);
    color: white;
    padding: 12px 25px;
    border-radius: 5px;
    text-transform: uppercase;
    font-weight: bold;
    transition: background-color 0.3s ease;
    border: none;
    cursor: pointer;
}

.btn:hover {
    background-color: #0056b3;
}

.btn.secondary-btn {
    background-color: var(--secondary-color);
}

.btn.secondary-btn:hover {
    background-color: #5a6268;
}

/* Header */
.header {
    background-color: var(--dark-bg);
    color: var(--light-text-color);
    padding: 15px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.8em;
    font-weight: bold;
    color: var(--light-text-color);
}

.main-nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

.main-nav ul li {
    margin-left: 30px;
}

.main-nav ul li a {
    color: var(--light-text-color);
    font-weight: 400;
    font-size: 1.1em;
    padding: 5px 0;
    position: relative;
}

.main-nav ul li a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    background: var(--primary-color);
    bottom: 0;
    left: 0;
    transition: width 0.3s ease-in-out;
}

.main-nav ul li a:hover::after {
    width: 100%;
}

.nav-toggle {
    display: none; /* Приховано за замовчуванням */
    background: none;
    border: none;
    cursor: pointer;
    padding: 0;
    width: 30px;
    height: 20px;
    position: relative;
}

.nav-toggle span {
    display: block;
    width: 100%;
    height: 3px;
    background: var(--light-text-color);
    margin-bottom: 5px;
    transition: all 0.3s ease;
}

.nav-toggle.open span:nth-child(1) {
    transform: rotate(45deg) translate(5px, 5px);
}
.nav-toggle.open span:nth-child(2) {
    opacity: 0;
}
.nav-toggle.open span:nth-child(3) {
    transform: rotate(-45deg) translate(5px, -5px);
}


/* Hero Section */
.hero-section {
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('../assets/images/hero-bg.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 60vh;
}

.hero-section h1 {
    font-size: 3.5em;
    margin-bottom: 20px;
    color: white;
}

.hero-section p {
    font-size: 1.3em;
    margin-bottom: 40px;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
}

/* Sections */
section {
    padding: 80px 0;
}

section:nth-of-type(even) {
    background-color: var(--light-bg);
}

section:nth-of-type(odd) {
    background-color: white;
}

h2 {
    text-align: center;
    font-size: 2.5em;
    margin-bottom: 60px;
    position: relative;
}

h2::after {
    content: '';
    position: absolute;
    width: 60px;
    height: 4px;
    background: var(--primary-color);
    bottom: -15px;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 2px;
}

/* About Section */
.about-section .grid-layout {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    align-items: center;
}

.about-section .image-content img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

/* Applications Section (Card Grid) */
.card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.card {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.card h3 {
    color: var(--primary-color);
    margin-bottom: 15px;
    font-size: 1.5em;
}

/* News Section */
.news-item {
    background-color: white;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    margin-bottom: 25px;
}

.news-item h3 {
    color: var(--dark-bg);
    font-size: 1.6em;
    margin-bottom: 10px;
}

.news-item .date {
    color: var(--secondary-color);
    font-size: 0.9em;
    margin-bottom: 10px;
}

.news-item .read-more {
    font-weight: bold;
}

/* Contact Section */
.contact-form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.contact-form input[type="text"],
.contact-form input[type="email"],
.contact-form textarea {
    width: 100%;
    padding: 15px;
    border: 1px solid var(--border-color);
    border-radius: 5px;
    font-family: var(--font-primary);
    font-size: 1em;
}

.contact-form textarea {
    resize: vertical;
}

.contact-form button {
    align-self: flex-start; /* Вирівнює кнопку до лівого краю */
}

/* Footer */
.footer {
    background-color: var(--dark-bg);
    color: var(--light-text-color);
    padding: 40px 0;
    text-align: center;
}

.footer .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.footer p {
    margin-bottom: 15px;
}

.social-links a {
    display: inline-block;
    margin: 0 10px;
}

.social-links img {
    width: 28px;
    height: 28px;
    filter: invert(100%); /* Робить іконки білими */
    transition: transform 0.3s ease;
}

.social-links img:hover {
    transform: translateY(-3px);
}

/* Адаптивність (Mobile Responsiveness) */
@media (max-width: 992px) {
    .main-nav {
        display: none; /* Приховуємо меню за замовчуванням на мобільних */
        position: absolute;
        top: 60px; /* Висота хедера */
        left: 0;
        width: 100%;
        background-color: var(--dark-bg);
        box-shadow: 0 5px 10px rgba(0,0,0,0.3);
        flex-direction: column;
        align-items: center;
        padding: 20px 0;
        z-index: 999;
    }
    .main-nav.active {
        display: flex; /* Показуємо меню при активному класі */
    }
    .main-nav ul {
        flex-direction: column;
        width: 100%;
        text-align: center;
    }
    .main-nav ul li {
        margin: 15px 0;
    }
    .nav-toggle {
        display: block; /* Показуємо бургер-іконку */
    }
    .hero-section h1 {
        font-size: 2.5em;
    }
    .hero-section p {
        font-size: 1.1em;
    }
    .about-section .grid-layout {
        grid-template-columns: 1fr; /* В один стовпець на мобільних */
        text-align: center;
    }
    .about-section .image-content {
        order: -1; /* Зображення над текстом на мобільних */
    }
}

@media (max-width: 768px) {
    h1 {
        font-size: 2.8em;
    }
    h2 {
        font-size: 2em;
    }
    section {
        padding: 60px 0;
    }
}

@media (max-width: 480px) {
    .hero-section {
        padding: 80px 15px;
    }
    .hero-section h1 {
        font-size: 2em;
    }
    .hero-section p {
        font-size: 1em;
    }
    .card {
        padding: 20px;
    }
    .news-item {
        padding: 20px;
    }
