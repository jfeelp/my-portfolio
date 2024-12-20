# my-portfolio
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моє модельне портфоліо | My Modeling Portfolio</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://via.placeholder.com/1920x500') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        header h1 {
            font-size: 3.5rem;
            margin: 0;
        }
        header p {
            font-size: 1.5rem;
        }
        nav {
            text-align: center;
            background: #333;
            color: white;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1rem;
        }
        .section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .about, .contact {
            text-align: center;
        }
        .bilingual p {
            margin: 10px 0;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Моє модельне портфоліо</h1>
        <p>My Modeling Portfolio</p>
    </header>

    <nav>
        <a href="#about">Про мене | About Me</a>
        <a href="#portfolio">Портфоліо | Portfolio</a>
        <a href="#contact">Контакти | Contact</a>
    </nav>

    <section id="about" class="section about bilingual">
        <h2>Про мене | About Me</h2>
        <p>Привіт! Я — модель, яка прагне створювати мистецтво та стиль.</p>
        <p>Hello! I am a model passionate about creating art and style.</p>
    </section>

    <section id="portfolio" class="section gallery bilingual">
        <h2>Портфоліо | Portfolio</h2>
        <p>Ознайомтесь з моїми найкращими роботами.</p>
        <p>Take a look at my best works.</p>
        <!-- Add your images here -->
        <img src="https://via.placeholder.com/300x400" alt="Sample Work">
        <img src="https://via.placeholder.com/300x400" alt="Sample Work">
        <img src="https://via.placeholder.com/300x400" alt="Sample Work">
        <img src="https://via.placeholder.com/300x400" alt="Sample Work">
    </section>

    <section id="contact" class="section contact bilingual">
        <h2>Контакти | Contact</h2>
        <p>Для пропозицій співпраці, будь ласка, звертайтеся:</p>
        <p>For collaboration inquiries, please reach out to:</p>
        <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
        <p>Instagram: <a href="https://instagram.com/yourprofile" target="_blank">@yourprofile</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Моє модельне портфоліо | My Modeling Portfolio. Всі права захищені.</p>
    </footer>
</body>
</html>
