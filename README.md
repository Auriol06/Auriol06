<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Site de Freelance</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        .portfolio, .contact {
            background: #fff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenue sur Mon Site de Freelance</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">À Propos</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="container">

    <section id="services" class="portfolio">
        <h2>Mes Services</h2>
        <p>Je propose des services de design graphique, rédaction et développement web.</p>
    </section>

    <section id="portfolio" class="portfolio">
        <h2>Mon Portfolio</h2>
        <p>Voici quelques-uns de mes travaux récents :</p>
        <ul>
            <li>Projet 1 - Description</li>
            <li>Projet 2 - Description</li>
            <li>Projet 3 - Description</li>
        </ul>
    </section>

    <section id="about" class="portfolio">
        <h2>À Propos</h2>
        <p>Je suis un freelance passionné avec plusieurs années d'expérience dans mon domaine.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contactez-moi</h2>
        <form>
            <label for="name">Nom :</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email :</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message :</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Envoyer">
        </form>
    </section>

</div>

<footer>
    <p>&copy; 2024 Mon Nom - Tous droits réservés</p>
</footer>

</body>
</html>
