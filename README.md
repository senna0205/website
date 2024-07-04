<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mijn Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welkom op mijn website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">Over</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Dit is de startpagina van mijn website.</p>
        </section>
        <section id="about">
            <h2>Over</h2>
            <p>Informatie over mij of mijn bedrijf.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Contactgegevens en een contactformulier.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Mijn Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1em;
    text-align: center;
}

nav ul {
    background-color: #333;
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin-right: 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 1em;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 0.5em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
